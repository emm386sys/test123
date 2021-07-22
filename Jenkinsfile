pipeline {

  agent any

  tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
  }

  stages {
    stage('Cleanup') {
      node('master) {
env.JAVA_HOME = "${tool 'jdk'}"

          sh "mvn clean"
      }
    }
  }
}
