pipeline {
    agent {
        docker { image 'python:3.7'}
    }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Print') {
            steps {
                sh 'python demo.py'
            }
        }
    }
}
