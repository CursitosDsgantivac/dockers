pipeline{
    agent any

    stages{
        stage('Hello'){
            steps{
                echo 'Hello world!'
            }
        }
        stage('show Dockers'){
            steps{
                sh "docker ps"
            }
        }
        stage('show docker images'){
            steps{
                sh "docker images"
            }
        }
        stage('custom hello world'){
            steps{
                echo 'Hello world from github baby!'
            }
        }
    }
}