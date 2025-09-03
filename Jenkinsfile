pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time:30, unit:'HOURS')
        disableConcurrentBuilds()
    }
    stages {
        stage('Build') {
            steps {
                echo 'This is Build'
            }
        }
        stage('Test') {
            steps {
                echo 'This is Test'
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is Deploy'
            }
        }
    }
}