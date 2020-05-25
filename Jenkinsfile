pipeline {
    agent { agent { label 'Docker' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
