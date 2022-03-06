pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi'
        sh 'java --version'
        sh 'gradle --version'
        sh 'gradle build'
      }
    }

  }
}