node {

  env.JAVA_HOME = "${tool 'jdk'}"
  stage("Cleanup") {
    env.JAVA_HOME = "${tool 'jdk'}"
withMaven {
      sh "mvn clean verify"
    }


  }

}
