pipeline {
    agent { 
        label 'Docker'
        docker { image 'golang' }
    }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
