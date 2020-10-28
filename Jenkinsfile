pipeline {
  agent any
    
  tools {
      nodejs 'NodeJS-15'
    }
    
  stages {
     
    stage('Build') {
      steps {
        sh 'npm install'
         
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'npm test'
      }
    }
  }
}