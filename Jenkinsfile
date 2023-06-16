pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 3000:3000 -u root --dns 172.17.0.1' 
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
