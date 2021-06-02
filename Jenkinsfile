pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git 'https://github.com/ynsaiyadav/assignment4_1.git'
            }
        }
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
