pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello from pipeline after readme file and webhook!"
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
