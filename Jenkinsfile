pipeline {
    agent any

    stages {
        stage('Mensaje') {
            steps {
                echo 'Hola..'
            }
        }
        stage('Test') {
            steps {
                C:\Users\Administrator\AppData\Local\Programs\Python\Python39\python.exe test_PruebaJenkinsPython.py
            }
        }
        stage('Finalizando') {
            steps {
                echo 'Tarea Cumplida....'
            }
        }
    }
}