pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Print') {
            steps {
                python demo.py
            }
        }
    }
}
