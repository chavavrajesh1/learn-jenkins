pipeline {
    agent {
        label 'AGENT-1'
    }
    options{
        timeout(time: 1, unit: 'seconds')
    }
    stages {
        stage('Build') {
            steps {
                echo 'This is build'
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