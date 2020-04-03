pipeline {
    agent { docker '${myimage}' }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
