pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build'
                echo 'Task: Compile and package the application code'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests'
                echo 'Task: Run unit tests and integration tests'
                echo 'Tool: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis'
                echo 'Task: Analyse code quality and check coding standards'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan'
                echo 'Task: Scan code for vulnerabilities'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging'
                echo 'Task: Deploy application to staging server'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging'
                echo 'Task: Test the application in staging environment'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production'
                echo 'Task: Deploy application to production server'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
