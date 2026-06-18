pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/USERNAME/selenium-jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}