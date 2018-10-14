pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'Hi' > msg
                cat msg
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                cat msg
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
