pipeline {
    agent {
         docker {
            image '${myimage}'
        }
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
