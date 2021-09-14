pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('testing') {
            steps {
                sh 'py.test'
            }
        }
    }
}
