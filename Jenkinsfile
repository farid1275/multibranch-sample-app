pipeline {
  agent any
  options {
    buildDiscarder logRotator(artifactDaysToKeepStra: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5'))
    disableConcurrentBuilds()
  }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
}
