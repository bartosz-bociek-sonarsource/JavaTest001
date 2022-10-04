pipeline {
  agent none
  stages {
    stage('gradlew') {
      environment {
        sonar = 'sonarqube'
      }
      steps {
        withGradle()
      }
    }

  }
}