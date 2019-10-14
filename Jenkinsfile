pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
        stage('run') {
            steps {
                sh 'echo "test"'
            }
        }
    }
}
