pipeline {

tools {
    maven 'maven'
    jdk 'jdk'
    dockerTool 'docker'
}


    agent {
        docker {
            image 'maven:3.8.1-adoptopenjdk-11'
            args '-v /root/.m2:/root/.m2'
        }
}

    stages {
        stage('Cleanup') { 
            steps {
      sh "mvn clean"
            }
        }
    }
}
