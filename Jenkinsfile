#!groovy
pipeline{
    agent any 
    stages{
        stage('docker-build'){
            steps{
                sh '/usr/bin/python3 main.py'
            }
        }
    }
}
