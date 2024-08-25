pipeline {
  agent any
  stages {
    stage('aa') {
      agent any
      environment {
        bbbbb = '222'
      }
      steps {
        sh 'echo params.aaa'
      }
    }

  }
  environment {
    aaaa = '11'
  }
}