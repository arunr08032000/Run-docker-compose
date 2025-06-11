pipeline {
    agent any
    environment {
      DOCKERHUB_CREDENTIALS = credentials('docker-dockerhub')
    }
    stages {
        stage('Run') {
            steps { 
                sh 'sudo docker-compose up -d' 
            }
        }
    }
}
