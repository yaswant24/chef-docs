pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo \'babu\''
      }
    }

    stage('dev') {
      steps {
        sh 'echo \'new build\''
      }
    }

    stage('prod') {
      steps {
        sh 'echo \'prod\''
      }
    }

  }
}