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
                cs = load './lib/cowsay.groovy'
                cs.main("mu")
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
