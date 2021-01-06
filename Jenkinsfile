pipeline {
    agent any

    tools {nodejs "npm"}

    stages {
        stage('Build') {
            steps {
                    sh """
                        npm install -g yarn
                        yarn install
                    """
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