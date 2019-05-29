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

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

         }

}