pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                withEnv(['PATH+EXTRA=/usr/local/bin/python']){
                sh 'python --version'
                }
            }
        }
    }
}