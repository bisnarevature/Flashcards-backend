pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withGradle() {
          sh 'gradle build'
        }

      }
    }

  }
}