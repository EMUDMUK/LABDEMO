pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                kubernetes { image 'maven:3-alpine' }
            }
            steps {
                sh 'mvn --version'
            }
        }
        stage('Front-end') {
            agent {
                kubernetes { image 'node:7-alpine' }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}
