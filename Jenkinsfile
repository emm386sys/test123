pipeline {

tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
}



    stages {
        stage('Cleanup') { 
            steps {
env.JAVA_HOME="${tool 'jdk'}"
      sh "mvn clean"
            }
        }
    }
}
