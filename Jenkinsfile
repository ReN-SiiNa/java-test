pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/java-ci-jenkins.git'
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
