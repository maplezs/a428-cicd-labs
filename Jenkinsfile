pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 3000:3000 -u root' 
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
