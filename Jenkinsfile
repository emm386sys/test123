
pipeline {
    agent any
    tools {
        maven 'apache-maven-$env.MVN_VERSION' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn clean'
            }
        }
    }
}
