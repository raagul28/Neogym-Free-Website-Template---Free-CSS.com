pipeline{
  agent any
  stages{
    stage("test"){
      agent{docker {image'gradle:8.2.0-jdk17-alpine'}
      reuseNode true}
      steps{
        echo 'Hii'
        
      }
     
  }
  }
}
  
