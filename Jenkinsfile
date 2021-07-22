pipeline {

tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
}

env.JAVA_HOME="${tool 'jdk'}"

print env.JAVA_HOME

    stages {
        stage('Cleanup') { 
            steps {
      sh "mvn clean"
            }
        }
    }
}
