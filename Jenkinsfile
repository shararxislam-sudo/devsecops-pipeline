pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building with Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit & integration tests with JUnit'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analyzing code with SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning vulnerabilities with Trivy'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS EC2 staging server'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running tests in staging environment'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS EC2 production server'
            }
        }
    }
}
