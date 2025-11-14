pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        sh 'echo \'hellow!\''
      }
    }

  }
  environment {
    CredentialsId = 'myjenkins'
  }
}