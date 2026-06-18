pipeline {
    agent any

    stages {

        stage('Build & Test') {
            steps {
                sh '/usr/bin/mvn clean test'
            }
        }

    }
}