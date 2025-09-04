pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Task:    Build the code using a build automation tool
                // Purpose: Compile and package the code
                // Tool:    Gradle
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                // Task:    Run unit and integration tests using test automation tools
                // Purpose: Ensuring the code functions and different components work together as expected 
                // Tools:   JUnit (unit testing), Selenium (integration testing)
            }
        }
        stage('Code Analysis') {
            steps {
                // Task:    Analyse the code using a code analysis tool
                // Purpose: Ensure the code meets industry standards
                // Tool:    SonarQube
            }
        }
        stage('Security Scan') {
            steps {
                // Task:    Perform a security scan on the code using a security tool
                // Purpose: Identify any vulnerabilities in the code
                // Tool:    Snyk
            }
        }
        stage('Deploy to Staging') {
            steps {
                // Task:    Deploy application to a staging server
                // Purpose: Test application in a safe, closed environment that mimics production
                // Tool:    Ansible
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                // Task:    Run integration tests on the staging environment
                // Purpose: Ensure application functions as expected in production-like environment
                // Tool:    Selenium
            }
        }
        stage('Deploy to Production') {
            steps {
                // Task:    Deploy the application to a production server
                // Purpose: Application is ready for real users after successful testing in earlier stages
                // Tool:    Ansible
            }
        }
    }
}