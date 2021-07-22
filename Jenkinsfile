node {

  env.JAVA_HOME = "${tool 'jdk'}"
  stage("Cleanup") {
    env.JAVA_HOME = "${tool 'jdk'}"

 withMaven(maven: 'maven-latest', globalMavenSettingsConfig: 'default-global-settings', mavenSettingsConfig: 'codice-maven-settings', mavenOpts: '${LARGE_MVN_OPTS} ${LINUX_MVN_RANDOM}', options: [artifactsPublisher(disabled: true), dependenciesFingerprintPublisher(disabled: true, includeScopeCompile: false, includeScopeProvided: false, includeScopeRuntime: false, includeSnapshotVersions: false)]) {
                
      sh 'mvn clean install'
  }
    }


  }

}
