pipeline {
    agent {
         docker {
            image '${myimage}'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
