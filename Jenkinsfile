
pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'
    }

    stages {
        stage('Checkout') {
            steps {
                deleteDir()
                git branch: 'main',
                    url: 'https://github.com/tejashwini-kurella/MavenJava.git'
            }
        }

        stage('Clean') {
            steps {
                bat 'mvn clean'
            }
        }

        stage('Install') {
            steps {
                bat 'mvn install'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }

        stage('Package') {
            steps {
                bat 'mvn package'
            }
        }
    }
}
