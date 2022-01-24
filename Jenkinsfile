#!/usr/bin/env groovy
pipeline{
    agent any
    tools{
        maven 'name of the installation'
    }
    stages{
        stage('Build'){
            steps{
                echo 'Building the application'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing the application'
                }
        }
        stage('Deploy'){
            steps{
               echo 'Deploying the application'
                }
        }
    }
}
