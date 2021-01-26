#!/usr/bin/env groovy

pipeline {
    agent any  
    stages {
        stage('Build Nginx Image') { 
            steps { 
                sh 'docker build -t ec2-54-173-108-195.compute-1.amazonaws.com:8083/nginx-server:${BUILD_NUMBER} .' 
               }
        }
        }
}
