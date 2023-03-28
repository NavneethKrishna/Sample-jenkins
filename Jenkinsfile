pipeline {
    agent any

    stages {
        stage('Job 1') {
            steps {
                sh '''
                echo "The Job 1 ran at $(date)"
                '''
            }
        }
        stage('Job 2') {
            steps {
                sh '''
                echo "The Job 2 ran at $(date)"
                '''
            }
        }
    }
}
