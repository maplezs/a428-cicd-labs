pipeline {
    agent {
        docker {
            image 'node:lst-buster-slim' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm i' 
            }
        }
    }
}
