pipeline {

    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('build stage') {
            steps {
                bat "mvn clean compile" 
        }
    }

         stage('test stage') {
             steps {
                bat "mvn test"
        }
    }
stage('deploy stage') {
             steps {
                bat "mvn deploy"
        }
    }
         }

}