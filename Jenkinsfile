pipeline {
    agent any

    stages {
        stage('SCM checkout') {
            steps {
                echo 'checkout step'
            }
        }
        stage('Build') {
            steps {
                 sh 'date'
            }
        }
        stage('Test') {
            steps {
               echo "hello redsup"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step'
            }
        }
    }
}
