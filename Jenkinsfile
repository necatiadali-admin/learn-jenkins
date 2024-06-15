pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                echo 'React App'
            }
        }
        stage('npm install') {
            steps {
                withNPM() {
                    echo 'Performing npm build...'
                    sh 'npm install'
                }
            }
        }
    }
