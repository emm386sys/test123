node {

  env.JAVA_HOME = "${tool 'jdk'}"
  stage("Cleanup") {
    env.JAVA_HOME = "${tool 'jdk'}"

withMaven(maven : 'apache-maven-3.6.1'){
      sh 'mvn clean install'
  }
    }


  }

}
