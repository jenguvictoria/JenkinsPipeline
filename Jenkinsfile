pipeline {
    agent { 
        node { 
            label 'ssh Test' 
        } 
    } 
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
    stage('Checkout') {
            steps {
                git branch: 'Test', url: 'https://github.com/jenguvictoria/JenkinsPipeline' 
            }
        }    
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

