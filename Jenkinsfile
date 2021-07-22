pipeline {

  agent any

  tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
  }

  stages {
    stage('Cleanup') {
      node {
        env.JAVA_HOME = "${tool 'jdk'}"

        steps {
          sh "mvn clean"
        }
      }
    }
  }
}
