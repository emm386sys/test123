pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
	dockerTool 'docker'
    }
    stages {
        stage('Cleanup') { 
            steps {
      sh "mvn clean"
            }
        }
    }
}
