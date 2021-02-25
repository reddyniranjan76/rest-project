pipeline
{
 agent any
 stages{
  stage('Build Application rest project'){
   steps{
   bat 'mvn clean install'
   }
   }
  stage('Deploy Application to Mulesoft Colud Hub'){
   steps{
   bat 'mvn package deploy -DmuleDeploy'
   }
   } 
   
  }
 }  
 