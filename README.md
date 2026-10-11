# MavenJava

## Overview
MavenJava is a Java project managed using Apache Maven. Maven is used to manage project dependencies, compile source code, run tests, and package the application.

## Technologies Used
- Java
- Apache Maven
- Git and GitHub
- Jenkins

## Build Lifecycle
The project follows these Maven build stages:

1. **Clean:** Removes previously generated build files.
2. **Compile:** Compiles the Java source code.
3. **Test:** Executes the available tests.
4. **Package:** Packages the compiled code into the appropriate artifact.
5. **Install:** Installs the generated artifact into the local Maven repository.

## Continuous Integration with Jenkins
Jenkins automates the build process using a Pipeline.

The pipeline includes:
- Cloning the source code from GitHub
- Cleaning previous build outputs
- Installing project dependencies and building the project
- Running tests
- Packaging the application
Webhook test: Jenkins automatic build verification.
## GitHub Webhook Integration
A GitHub webhook is configured to notify Jenkins whenever code is pushed to the repository. This allows Jenkins to trigger the configured pipeline automatically.

## Objective
To understand Maven project builds, version control using Git and GitHub, and Continuous Integration using Jenkins.
Testing automatic Jenkins CI using GitHub webhooks.
Testing automatic Jenkins CI using GitHub webhooks.
