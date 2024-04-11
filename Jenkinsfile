pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'build success'
                sh 'node -v'
            }
        }
        stage('Test') {
            steps {
                echo 'test success'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy success'
            }
        }
        stage('Clean up') {
            steps {
                echo 'clean up success'
            }
        }
    }
}