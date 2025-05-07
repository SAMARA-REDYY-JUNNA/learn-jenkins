pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
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
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is a deploy step'
            }
        }
    }
}