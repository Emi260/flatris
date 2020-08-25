pipeline {
  agent any
  stages {
    stage('t') {
      steps {
        echo 'd'
      }
    }

    stage('imp') {
      steps {
        input(message: 'estas de acuerdo', ok: 'Obvio')
      }
    }

  }
}