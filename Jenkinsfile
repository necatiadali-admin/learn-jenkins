pipeline {
    agent { dockerfile true }
    stages {
        stage('Stage') {
            steps {
                echo 'React App'
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                    echo 'Performing npm build...'
                    sh 'npm run dev'
            }
        }
    }
}

