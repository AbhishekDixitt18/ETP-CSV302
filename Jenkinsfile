pipeline {
    agent any

    tools {
        maven 'Maven3'
    }

    stages {
        stage('Build & Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}