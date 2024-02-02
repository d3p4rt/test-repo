pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                /usr/local/bin/kubectl get nodes
            }
        }
        stage('Test') {
            steps {
                /usr/local/bin/kubectl get namespaces
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
