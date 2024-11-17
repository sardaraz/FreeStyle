pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Run the Python code
                'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                'java HelloWorld'
            }
        }
    }
}
