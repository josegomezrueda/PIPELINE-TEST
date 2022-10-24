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
        stage('Build') {
            steps {
                sh 'npm version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
