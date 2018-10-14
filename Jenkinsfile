pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'echo Hi > msg'
                sh 'cat msg'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'cat msg'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
