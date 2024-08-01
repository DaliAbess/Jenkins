pipeline {
    agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {

                sh 'df -H'
                sh 'ls -lsa'
                
            }
        }
        stage('test') {
            steps {
                sh 'cat test.txt'
                sh 'sleep 1'
                
            }
        }
    }
}
