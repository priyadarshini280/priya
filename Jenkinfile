 pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Samp.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Samp'
            }
        }
    }
}
