pipeline {
   agent any
   stages {
   stage ('compile stage') {
   steps{
   withMaven(maven :'Maven'){
   sh 'mvn clean compile'
   }
   }      }
   }
}