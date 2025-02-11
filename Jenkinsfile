pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
                stage('test') {
            steps {
                echo "stage2"
                sh 'ls'
                sh "pwd"
                sh "touch test.txt"
                echo 'not using shell in the Jenkinsfile'
            }
        }
                stage('deploy') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'ls'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}