pipeline {
    agent any
    tools {
        nodejs 'NodeJs'
    }
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
                    sh 'npm run build'
            }
        }
         stage('Run') {
            steps {
                    echo 'Performing npm run dev...'
                    sh 'npm run dev'
            }
        }
    }
}

