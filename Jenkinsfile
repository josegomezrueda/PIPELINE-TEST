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
        stage('Building') {
            steps {
                sh 'npm install'
                sh 'npm rebuild'
            }
        }
        stage('Testing') {
            steps {
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
