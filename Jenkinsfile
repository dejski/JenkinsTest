pipeline {
  agent any
  stages {
    stage('s1') {
      steps {
        echo 't1'
      }
    }
    stage('s2') {
      steps {
        bat 't1.bat'
      }
    }
  }
}