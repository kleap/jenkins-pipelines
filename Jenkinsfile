pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'node --version'
                bat 'yarn'
                bat 'yarn build'
            }
        }
    }
}