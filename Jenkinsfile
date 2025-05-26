pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'javac src\\HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running...'
                bat 'java -cp src HelloWorld'
            }
        }
    }
}
