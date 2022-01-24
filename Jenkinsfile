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
                      ./mvnw compile
                    }
            }
        stage('Test'){
                steps{
                    echo 'Testing the application'
                    ./mvnw test
                    }
                }

        stage('Build'){
            steps{
                echo 'Building the application'
                ./mvnw package
            }
        }

        stage('Deploy'){
            steps{
               echo 'Deploying the application'
                }
        }
    }
}
