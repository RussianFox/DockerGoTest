pipeline {
    agent { label 'Docker' }
    stages {
        stage('build') {
            agent { docker { image 'golang' } }
            steps {
                sh 'go version'
            }
        }
    }
}
