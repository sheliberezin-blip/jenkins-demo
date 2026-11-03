pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello from a Jenkinsfile stored in Git!'
                echo 'This change is tracked in git history!'
            }
        }
    }
}
