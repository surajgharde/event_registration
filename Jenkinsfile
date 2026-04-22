pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/surajgharde/event_registration.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
