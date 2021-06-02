pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo hello'
      }
    }

    stage('Unit') {
      steps {
        sh 'mkdir app'
        dir(path: '/app') {
          sh 'ls'
        }

      }
    }

  }
}