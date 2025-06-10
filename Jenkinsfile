pipeline {
    agent { docker { image 'python:3.12.9' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('unittest') {
            steps {
                sh 'pytest'
            }
        }
    }
}
