#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {           
           echo 'Building..'
        }         
       stage('Test'){       
          sh './az-resources/create-vm.sh'
       }
    }
}
