pipeline {

agent any

tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
}


node{
env.JAVA_HOME="${tool 'jdk'}"

    stages {
        stage('Cleanup') { 
            steps {
      sh "mvn clean"
            }
        }
    }
}
}
