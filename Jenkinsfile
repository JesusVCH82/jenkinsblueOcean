pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        echo 'Compilando'
        sh 'date'
      }
    }

    stage('Testing') {
      steps {
        echo 'Test '
        sh 'pwd'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Program'
      }
    }

  }
  environment {
    AUTHOR = 'Jesus'
  }
}