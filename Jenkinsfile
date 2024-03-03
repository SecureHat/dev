pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. pipeline'
               
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'whoami'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'date'
            }
        }
    }
}
