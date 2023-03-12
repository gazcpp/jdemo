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