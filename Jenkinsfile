pipeline {
    agent any

    stage('Compile') {
    steps {
        sh 'javac Helloworld.java'
    }
}
        stage('Run') {
            steps {
                sh 'java Helloworld'
            }
        }
    }
}
