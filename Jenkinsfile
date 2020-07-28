pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "this is the $BUILD_NUMBER of the $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}