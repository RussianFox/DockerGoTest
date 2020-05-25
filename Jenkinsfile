pipeline {
    node('Docker') {
        agent { docker { image 'golang' } }
        stages {
            stage('build') {
                steps {
                    sh 'go version'
                }
            }
        }
    }
}
