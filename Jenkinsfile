pipeline {
  
     agent any 
  stage('Build') {
    steps{
        sh '/home/diallo/Téléchargements/maven/bin/mvn clean install'
    }
    
  }
  stage('Test'){
    steps{
      sh '/home/diallo/Téléchargements/maven/bin/mvn test'
         
    }
  
  }
    
  
}
