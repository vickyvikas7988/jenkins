#!groovy
pipeline{
    agent { label 'docker_io'
    }  
    stages{
        stage('docker-build'){
            steps{
                sh 'docker build .'
            }
        }
    }
}
