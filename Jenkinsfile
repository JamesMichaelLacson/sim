pipeline {
    agent { label 'master' }
    stages {
        stage('run') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'python pipeline.py'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
