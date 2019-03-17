pipeline {
    agent { docker { image 'node:8.15' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
