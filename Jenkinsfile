pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Contruindo Ambiente.'
            }
        }
        stage('Test') {
            steps {
                script{
                build job: 'Gatinho pra executar'
                }                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}