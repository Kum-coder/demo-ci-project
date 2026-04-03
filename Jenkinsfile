node {

    stage('Checkout Code') {
        checkout scm
    }

    stage('Read File') {
        def content = readFile('kumar.txt')
        echo content
    }

}