pipeline {
    agent {
        docker {
            image 'docker.io/tirasmuturi/devops:nodetest1' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}