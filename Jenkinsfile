pipeline {
    agent any
    tools {
        nodejs '16.18.0'
    }
    stages {
        stage('Check npm version') {
            steps {
                sh 'npm version'
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
