//pipeline {
//    agent { docker { image 'golang:1.23.1-alpine3.20' } }
//    stages {
//        stage('Checkout') {
//            steps {
//                sh 'go version'
//		sh 'echo helllllllo'
//            }
//        }
//    }
//}

pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
		script{
			img='golang:1.23.1-alpine3.20'
			docker.image(${img}").run('-d -p 80:80')
		}
                //sh 'python --version'
            }
        }
    }
}
