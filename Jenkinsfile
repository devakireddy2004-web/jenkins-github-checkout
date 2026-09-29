pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/devakireddy2004-web/jenkins-github-checkout.git'
            }
        }

        stage('Verify Workspace') {
            steps {
                bat 'cd'
                bat 'dir'
                bat 'whoami'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }
    }
}
