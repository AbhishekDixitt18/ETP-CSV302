pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                git "https://github.com/AbhishekDixitt18/ETP-CSV302.git"
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}