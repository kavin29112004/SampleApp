pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/kavin29112004/SampleApp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
