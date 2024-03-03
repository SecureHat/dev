pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'you are great'
               
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'my god'
            }
        }
    }
}
