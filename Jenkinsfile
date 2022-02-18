pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Staging') {
            steps {
                echo 'Staging to repository'
            }
        }
        stage('Delivery') {
            steps {
                echo 'Automaticaly release to repository'
            }
        }
        stage('Deployment') {
            steps {
                echo 'Automaticaly deploy to production'
            }
        }
        
    }
}
