pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
                sh 'echo Running build...'
            }
        }
        stage('Test') {
            steps {
                echo "Testing branch: ${env.BRANCH_NAME}"
                sh 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying branch: ${env.BRANCH_NAME}"
                sh 'echo Deploying to production...'
            }
        }
    }
}

