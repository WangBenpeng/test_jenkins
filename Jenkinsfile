pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn package'
                sh 'ls'
                sh 'echo "hello world"'
            }
        }
    }
}