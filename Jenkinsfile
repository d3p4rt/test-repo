pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh'''
                /usr/local/bin/kubectl get nodes
                '''
            }
        }
        stage('Test') {
            steps {
                sh'''
                /usr/local/bin/kubectl get namespaces
                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
