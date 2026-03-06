pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building Node.js app'
            }
        }
        stage('Run App') {
            steps {
                bat 'node app.js'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing complete'
            }
        }
    }
}