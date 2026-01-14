pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Replace with your repository URL
                git 'https://github.com/nareshmorkhade/pipeline.git'
            }
        }
        stage('Build') {
            steps {
               sh 'ls-l'
            }
        }
        stage('Test') {
            steps {
                // Example: Run tests and aggregate reports
                
                // junit '**/target/surefire-reports/TEST-*.xml' // Example for JUnit plugin
            }
        }
        stage('Deploy') {
            steps {
                // Example: Deploy to a staging or production environment
                
            }
        }
    }
}
