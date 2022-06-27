pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        sh 'perl --version'
      }
    }
    stage('hello') {
      steps {
        sh 'perk hello.pl'
      }
    }
  }
}