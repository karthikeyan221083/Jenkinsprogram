pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac addition.py'
            }
        }

        stage('Run') {
            steps {
                sh 'addition'
            }
        }
    }
}
