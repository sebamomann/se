pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('stage 2') {
            steps {
                sh 'echo hi'
            }
        }
    }
}
