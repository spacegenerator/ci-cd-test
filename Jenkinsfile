pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Erkmustech to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy started"
                sh 'echo using shell within Jenkinsfile'
                echo 'Succesfullly deployed from local'
            }
        }
    }
}