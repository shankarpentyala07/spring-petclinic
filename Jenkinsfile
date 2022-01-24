#!/usr/bin/env groovy
pipeline{
    agent any
    tools{
        maven 'maven-3.8.4'
    }
    stages{

           stage('Compile'){
               steps{
                     echo 'Compiling the application'
                      sh './mvnw compile'
                    }
            }
        stage('Test'){
                steps{
                    echo 'Testing the application'
                    sh './mvnw test'
                    }
                }

        stage('Build'){
            steps{
                echo 'Building the application'
                sh './mvnw package'
            }
        }

        stage('Deploy'){
            steps{
               echo 'Deploying the application'
                }
        }
    }
}
