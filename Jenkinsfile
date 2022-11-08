@Library('cowsay')_
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
                echo 'Testing...'
                template("mu")
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
