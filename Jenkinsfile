pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('hello world!') {
            steps {
                sh 'echo "hello world"'
            }
        }
    }
}
