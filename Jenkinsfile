pipeline {
    agent any
    environment {
      DOCKERHUB_CREDENTIALS = credentials('docker-dockerhub')
    }
    stages {
        stage('Run') {
            steps { 
                sh 'echo 'arun' | sudo -S docker-compose up -d' 
            }
        }
    }
}
