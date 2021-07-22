pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
	docker 'docker'
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
