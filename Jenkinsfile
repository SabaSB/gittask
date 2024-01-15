pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running Building Automation'
        sh './gradlew build --no-daemon'
      }
    }
  }
}
