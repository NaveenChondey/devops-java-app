pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/NaveenChondey/devops-java-app.git'
            }
        }

        stage('Success') {
            steps {
                echo 'Pipeline executed successfully!'
            }
        }
    }
}
