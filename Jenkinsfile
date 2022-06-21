pipeline{
    agent any

    stages{
        stage('Hello'){
            echo 'Hello world!'
        }
        stage('show Dockers'){
            sh "docker ps"
        }
        stage('show docker images'){
            sh "docker images"
        }
    }
}