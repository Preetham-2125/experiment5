pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Add.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Add'
            }
        }
    }
}
