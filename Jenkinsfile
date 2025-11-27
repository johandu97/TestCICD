pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Show Webhook Payload') {
            steps {
                script {
                    echo "Webhook Triggered!"
                }
            }
        }
    }
}
