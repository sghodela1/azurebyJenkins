#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {  
            steps{
           echo 'Building..'
            }
        }         
       stage('Test'){  
           steps{
          sh './az-resources/create-vm.sh'
           }
       }
    }
}
