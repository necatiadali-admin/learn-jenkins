pipeline {
    agent any
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

