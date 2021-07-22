
pipeline {
    agent any
    tools {
        maven 'maven' 
    }
    stages {
        stage('Example') {
            steps {
		print(env.MVN_VERSION)
                sh 'mvn clean'
            }
        }
    }
}
