pipeline {
    agent any
    stages {
        stage('Example') {
         	agent { docker 'maven:3-alpine' } 
            	steps {
                  sh """
                  sleep 200
               		mvn compile
                  """
            }
        }
    }
}
