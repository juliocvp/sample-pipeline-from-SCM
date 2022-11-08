pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... test'
                script{
                    cowsay = load 'cowsay.groovy'
                    cowsay.template("mu")
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
