pipeline {
    agent any

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
