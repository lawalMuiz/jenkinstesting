pipeline {
    agent any
    
    stages {
        stage('Print ENVs') {
            steps {
                sh 'printenv'
            }
        }
        stage('Git Version') {
            steps {
                sh 'git --version'
            }
        }
        stage('Get Docker') {
            steps {
                sh 'docker version'
            }
        }
    }
}
