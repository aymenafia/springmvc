pipeline {
agent any
stages{
  
  
  
  stage('Build'){
    steps{
    sh '/Users/mohamedaymenafia/Downloads/apache-maven-3.5.3 clean install'
    }
  }
    
    stage('Test'){
    steps{
    sh '/usr/local/apache-maven/bin/mvn test'
    }
   }
    
}
}
