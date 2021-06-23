pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true' 
    }

    stages {
        stage('build') {
            steps {
                echo 'building app'
                // sh 'npm install'
                // sh 'npm run build'
            }
        }

        stage('test') {
            steps {
                echo 'testing app'
                // sh 'npm run test'
            }
        }

        stage('run') {
            steps {
                echo 'running app'
                // sh 'npm start'
            }
        }
    }
}