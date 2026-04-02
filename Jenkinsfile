pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/Kum-coder/demo-ci-project.git'
            }
        }

        stage('Read File') {
            steps {
                sh 'cat kumar.txt'
            }
        }
    }
}