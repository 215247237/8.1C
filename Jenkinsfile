pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Task:    Build the code using a build automation tool
                // Purpose: Compile and package the code
                // Tool:    Gradle
                echo "Stage 1: Build"
                echo "Building code using Gradle..."
                echo "TESTTTTTTT"
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                // Task:    Run unit and integration tests using test automation tools
                // Purpose: Ensuring the code functions and different components work together as expected 
                // Tools:   JUnit (unit testing), Selenium (integration testing)
                echo "Stage 2: Unit and Integration Tests"
                echo "Running unit and integration tests on code using JUnit and Selenium..."
            }
        }
        stage('Code Analysis') {
            steps {
                // Task:    Analyse the code using a code analysis tool
                // Purpose: Ensure the code meets industry standards
                // Tool:    SonarQube
                echo "Stage 3: Code Analysis"
                echo "Analysing code using SonarQube..."
            }
        }
        stage('Security Scan') {
            steps {
                // Task:    Perform a security scan on the code using a security tool
                // Purpose: Identify any vulnerabilities in the code
                // Tool:    Snyk
                echo "Stage 4: Security Scan"
                echo "Performing security scan on code using Snyk..."
            }
        }
        stage('Deploy to Staging') {
            steps {
                // Task:    Deploy application to a staging server
                // Purpose: Test application in a safe, closed environment that mimics production
                // Tool:    Ansible
                echo "Stage 5: Deploy to Staging"
                echo "Deploying application to staging server using Ansible..."
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                // Task:    Run integration tests on the staging environment
                // Purpose: Ensure application functions as expected in production-like environment
                // Tool:    Selenium
                echo "Stage 6: Integration Tests on Staging"
                echo "Running integration tests on application in staging environment using Selenium..."
            }
        }
        stage('Deploy to Production') {
            steps {
                // Task:    Deploy the application to a production server
                // Purpose: Application is ready for real users after successful testing in earlier stages
                // Tool:    Ansible
                echo "Stage 7: Deploy to Production"
                echo "Deploying application to a production server using Ansible..."
            }
        }
    }
}