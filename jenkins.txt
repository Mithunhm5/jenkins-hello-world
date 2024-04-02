pipeline {
    agent { any } // Run on any available node

    stages {
        stage('Print Hello World') {
            steps {
                script {
                    // Print "Hello World" message to console
                    echo "Hello World!"
                }
            }
        }
    }
}
