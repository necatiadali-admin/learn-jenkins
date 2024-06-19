pipeline {
    agent any
    tools {
        nodejs 'NodeJs'
    }
    stages {
        stage('Initialize') {
            steps {
                echo 'React App'
            }
        }
        stage('Build') {
            steps {
                    echo 'Performing npm build...'
                    sh 'npm install'
            }
        }
    }
}

