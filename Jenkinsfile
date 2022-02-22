pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi'
        sh 'gradle wrapper'
        sh '''

gradlew build'''
      }
    }

  }
}