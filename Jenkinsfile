pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... test'
                script{
                    def cs = load "./lib/cowsay.groovy"
                    cs.main(args:"mu")
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
