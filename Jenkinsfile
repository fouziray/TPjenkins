pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''gradle --version
&& gradle build'''
      }
    }

  }
}