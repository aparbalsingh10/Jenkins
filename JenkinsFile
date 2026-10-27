pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                checkout scm
                echo 'Code pulled successfully from GitHub!'
            }
        }

        stage('Verify Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
