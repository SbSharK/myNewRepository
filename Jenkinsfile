pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'Compile Phase'
                javac HelloName.java 
            }
        }
        stage('run') {
            steps {
                echo 'Run Phase'
                java HelloName
            }
        }
        stage('test') {
            steps {
                echo 'Test Phase'
            }
        }
    }
}
