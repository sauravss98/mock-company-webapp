pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './gradlew test'
            }
        }
    }
}
