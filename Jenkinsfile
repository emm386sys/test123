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
      sh "mvn clean"
            }
        }
    }
}
