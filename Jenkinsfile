pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Run the Python code
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
