#pipeline {
#    agent { docker { image 'golang:1.23.1-alpine3.20' } }
#    stages {
#        stage('Checkout') {
#            steps {
#                sh 'go version'
#		sh 'echo helllllllo'
#            }
#        }
#    }
#}

pipeline {
    agent { docker { image 'python:3.12.1-alpine3.19' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
