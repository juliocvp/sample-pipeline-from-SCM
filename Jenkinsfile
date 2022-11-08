pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... test'
                script{
                    cowsay = load 'cowsay.groovy'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                cowsay.template("mu")
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
