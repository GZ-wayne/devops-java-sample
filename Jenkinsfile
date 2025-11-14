pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        sh 'echo \'Hello world!\''
      }
    }

  }
  environment {
    credentials = '(\'myjenkins\')'
  }
}