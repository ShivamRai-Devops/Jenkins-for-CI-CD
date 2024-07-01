pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "No tests implemented"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}

