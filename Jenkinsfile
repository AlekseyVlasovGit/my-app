pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn package"
            }
        }
        stage('--test--') {
            steps {
                bat "mvn package"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}