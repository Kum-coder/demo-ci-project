pipeline {
    agent any

    stages {

        stage('Read File') {
            steps {
                script {
                    def content = readFile 'kumar.txt'
                    echo content
                }
            }
        }

    }
}