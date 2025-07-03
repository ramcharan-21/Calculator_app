pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/YOUR_USERNAME/calculator-devops.git'
            }
        }
        stage('Build & Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}