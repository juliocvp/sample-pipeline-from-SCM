// Jenkinsfile
@Library('cowsay') _
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... test'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing... prueba 2'
                cowsay 'mu'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
