pipeline {
    agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {

                
                sh 'lss'
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
