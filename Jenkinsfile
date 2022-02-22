pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi'
        sh 'gradle build'
        sh '''

gradlew.bat build'''
      }
    }

  }
}