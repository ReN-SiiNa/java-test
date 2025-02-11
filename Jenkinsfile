pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/ReN-SiiNa/java-test.git'
            }
        }
        stage('Compile Java Code') {
            steps {
                sh 'javac TimestampPrinter.java'
            }
        }
        stage('Run Program') {
            steps {
                sh 'java TimestampPrinter'
            }
        }
    }
}
