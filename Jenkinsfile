pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage('Cleanup') { 
            steps {
 withMaven {
      sh "mvn clean y"
    } 
            }
        }
    }
}
