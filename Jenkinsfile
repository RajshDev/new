pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from GitHub with credentials
                git url: 'https://github.com/RajshDev/new.git', branch: 'main', credentialsId: 'github-credentials'
            }
        }
        stage('Print Message') {
            steps {
                echo 'king'
            }
        }
    }
}
