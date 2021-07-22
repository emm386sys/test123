pipeline {
    agent any
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
