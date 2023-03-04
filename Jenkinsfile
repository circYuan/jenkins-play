pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'echo "hello!"'
      }
    }

    stage('run') {
      steps {
        sh 'python3 t1.py'
      }
    }

  }
}