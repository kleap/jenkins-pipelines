pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'node --version'
                bat 'yarn'
                bat 'mkdir build && copy index.html build\\index.html'
            }
        }
    }
}