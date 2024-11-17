pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Run the Python code
               bash 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
               bash 'java HelloWorld'
            }
        }
    }
}
