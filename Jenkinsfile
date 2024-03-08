pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Compile Java code
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                // Run Java application
                sh 'java HelloWorld'
            }
        }
    }
}
