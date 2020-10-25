pipeline {
    agent any

    stages {
        stage('Mensaje') {
            steps {
                bat 'echo "Hola.." '
            }
        }
        stage('Test') {
            steps {
                bat 'py test_PruebaJenkinsPython.py'
            }
        }
        stage('Finalizando') {
            steps {
                bat 'echo "Tarea Cumplida...."'
            }
        }
    }
}