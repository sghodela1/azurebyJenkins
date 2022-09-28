#!groovy
node('node'){
    currentBuild.result = "SUCCESS"
    try {

      stage('Checkout'){
          checkout scm
       }
       stage('Test'){       
          sh './az-resources/create-vm.sh'
       }
     }
    catch (err) {
        currentBuild.result = "FAILURE"
        throw err
    }
}
