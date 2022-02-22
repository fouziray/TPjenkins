pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi'
        sh 'gradle build'
        sh '''post {
always {
echo "Build stage complete" }
failure {
echo "Build failed"}
success {
echo "Build succeeded" }
}'''
        }
      }

    }
  }