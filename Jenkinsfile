node {

tools {
  maven 'maven'
  jdk 'jdk'
  dockerTool 'docker'
}

  env.JAVA_HOME = "${tool 'jdk'}"
  stage("Cleanup") {
    env.JAVA_HOME = "${tool 'jdk'}"

    sh "mvn clean"

  }

}
