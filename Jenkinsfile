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
        stage('install docker') {
            steps {
                sh 'sudo yum install docker'
            }
        }
    }
}
