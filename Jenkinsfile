pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "$BUILD_NUMBER of $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}