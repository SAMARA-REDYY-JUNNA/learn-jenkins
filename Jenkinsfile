pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo this is a build step'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this is a test step'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is a deploy step'
            }
        }
    }
}