pipeline {
  agent any
  stages {
    stage('stage-1') {
      steps {
        sh 'echo "this is a build number $BUILD_NUMBER of $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}