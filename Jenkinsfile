pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build Stage Started'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }

        stage('Deploy') {
            steps {
                sh 'chmod +x deploy.sh'
                sh './deploy.sh'
            }
        }
    }
}
