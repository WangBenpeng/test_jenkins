pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn package'
                sh 'ls'
                sh 'java -jar target/*.jar --server.port=8010'
                sh 'curl http://localhost:8010/hello'
            }
        }
    }
}