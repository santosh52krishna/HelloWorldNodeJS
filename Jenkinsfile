pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git(url: 'https://github.com/santosh52krishna/HelloWorldNodeJS.git', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'sh \'npm install\''
      }
    }
  }
}