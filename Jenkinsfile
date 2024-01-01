pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        script {
          checkout scm
          scripts script/build.sh
        }

      }
    }

  }
}