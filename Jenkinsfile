pipeline {
    agent any

    stages {
        stage ('build') {
            steps{
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage ('test') {
            steps{
                echo 'Test stage executed.'
            }
        }

        stage ('deploy') {
            steps{
                echo 'Deploy stage executed.'
            }
        }
    }
}