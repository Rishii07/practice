pipeline {
    agent any
    
    tools {
        jdk 'java' // Replace 'YOUR_JDK_NAME' with the name you specified in the Jenkins configuration
    }
    
    stages {
        stage('Build') {
            steps {
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
