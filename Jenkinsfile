#!/usr/bin/env groovy

pipeline {
    agent any  
    stages {
        stage('Build Nginx Image') { 
            steps { 
                sh 'docker build -t gcr.io/devops-302214/nginx-server:v1.1.0 .'
                sh 'docker push gcr.io/devops-302214/nginx-server:v1.1.0'
               }
        }
        }
}
