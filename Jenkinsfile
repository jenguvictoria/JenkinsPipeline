pipeline {
    agent { 
        node { 
            label 'ssh Dev' 
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
                git branch: 'Dev', url: 'https://github.com/jenguvictoria/JenkinsPipeline' 
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

