pipeline {
  
     agent any 
  stages('Build') {
    steps{
        sh '/home/diallo/Téléchargements/maven/bin/mvn clean install'
    }
    
  }
  stages('Test'){
    steps{
      sh '/home/diallo/Téléchargements/maven/bin/mvn test'
         
    }
  
  }
    
  
}
