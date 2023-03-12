pipeline {
    agent {
        node {
            label 'docker-agent-alpine'
            }
      }
    stages {
        stage('Build') {
            steps {
                sh '''
                echo "Building.."
                '''
            }
        }
        stage('Test') {
            steps {
                sh '''
                echo "Testing.."
                echo "Run testing."
                '''
            }
        }
        stage('Deliver') {
            steps {
                sh '''
                echo 'Deliver....'
                '''
            }
        }
    }
}