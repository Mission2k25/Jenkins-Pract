pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               script{
                 sh """
                    echo "Hello, this is build demo"
                 """
               }
            }
        }
        stage('Test') {
            steps {
                script{
                 sh """
                    echo "Hello, this is test demo"
                 """
                }
            }
        }
        stage('Deploy') {
            steps {
                script{
                 sh """
                    echo "Hello, this is deployment demo"
                 """
                }
            }
        }
    }
}
