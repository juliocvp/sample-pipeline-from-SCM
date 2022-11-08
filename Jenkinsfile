pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... test'
                script{
                    load 'cowsay.groovy'.template("mu")
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
