pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "HELLO PRASAD"
            }
        }
        stage('build') {
            steps {
                sh 'gcc hello.c -o output'
                sh './output'
            }
    }
}
