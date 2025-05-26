pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'javac Helloworld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running...'
                bat 'Helloworld'
            }
        }
    }
}
