pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('test1') {
            steps {
                sh 'echo hi'
            }
        }
        stage('test') {
            steps {
                sh 'echo tests are fine'
            }
        }
    }
}
