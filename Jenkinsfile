pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac add.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java add'
            }
        }
    }
}
