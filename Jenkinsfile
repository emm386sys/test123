node {

  env.JAVA_HOME = "${tool 'jdk'}"
  stage("Cleanup") {
    env.JAVA_HOME = "${tool 'jdk'}"
withMaven {
   withMaven(maven:'Maven_3_3_9') {
      sh 'mvn clean install'
  }
    }


  }

}
