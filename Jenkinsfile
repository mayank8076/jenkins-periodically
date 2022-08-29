pipeline {
    agent any
    stages {
        stage('Version') {
            steps {
                script {
                    sh 'python --version'
                }
            }
        }
        
        stage('Hello') {
            steps {
                script {
                    sh 'python hello-world.py'
                }
            }
        }


    }
}
