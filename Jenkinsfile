pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                withEnv(['PATH=$PATH:/usr/local/bin/python']){
                sh 'python --version'
                }
            }
        }
    }
}