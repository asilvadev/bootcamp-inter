pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Contruindo Ambiente...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testando...',
                build job: 'Gatinho pra executar',
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}