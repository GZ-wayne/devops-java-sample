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
    gitHubConnection = 'myjenkins'
  }
}