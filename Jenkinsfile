pipeline {
  agent any
  stages {
    stage('Step1') {
      steps {
        pwd(tmp: true)
      }
    }

    stage('Step2') {
      steps {
        echo 'Hi there!'
        sleep 5
      }
    }

  }
}