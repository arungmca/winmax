pipeline {
    agent any
    
    stages {
        stage('Information'){
            steps {
                echo 'Welcome to Build life'
            }                    
        }

        stage('Demo Publisher'){
            when {
                branch "develop"
            }
            steps {
                echo 'Develop branch build'
            }                    
        }

        stage('Production'){
            when {
                branch "main"
            }
            steps {
                echo 'Main Branch build'
            }                    
        }
    }
}