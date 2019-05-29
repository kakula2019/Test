pipeline {

    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn clean compile" 
        }
    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

          stage('deploy stage') {
              steps {
                bat "mvn dep"
        }
    }

  }

}