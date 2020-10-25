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
                bat 'C:/Users/Administrator/AppData/Local/Programs/Python/Python39/python.exe test_PruebaJenkinsPython.py'
            }
        }
        stage('Finalizando') {
            steps {
                bat 'echo "Tarea Cumplida...." '
            }
        }
    }
}