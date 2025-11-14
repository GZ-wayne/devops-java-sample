pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        git(url: 'https://github.com/GZ-wayne/devops-java-sample.git', branch: 'master', credentialsId: 'myjenkins')
      }
    }

  }
  environment {
    CredentialsId = 'myjenkins'
  }
}