pipeline {
    agent any

    tools {
        jdk 'jdk17'
        maven 'maven3'
    }
  
    stages {
        
         stage('Install') {
            steps {
                sh "mvn install"
            }
        }

    }
}
