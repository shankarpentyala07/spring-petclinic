#!/usr/bin/env groovy
pipeline{
    agent any
    tools{
        maven 'maven-3.8.4'
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
