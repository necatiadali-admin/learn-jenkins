pipeline {
    agent any
    tools {nodejs "nodejs"}
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

