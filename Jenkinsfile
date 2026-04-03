node {

    stage('Checkout Code') {
        checkout scm
    }

    stage('Read File') {
        def content = readFile('kumar.txt')
        echo "File Content:\n${content}"
    }

    stage('Line Count') {
        def content = readFile('kumar.txt')
        def lines = content.split("\n")
        echo "Total Lines: ${lines.size()}"
    }

    stage('Word Check') {
        def content = readFile('kumar.txt')

        if(content.contains("Jenkins")) {
            echo "✅ Word 'Jenkins' found"
        } else {
            error "❌ Word 'Jenkins' NOT found → Build Failed"
        }
    }

}