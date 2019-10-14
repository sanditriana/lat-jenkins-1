pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker run php php -version'
            }
        }
        stage('run') {
            steps {
                sh 'echo "test"'
            }
        }
    }
}
