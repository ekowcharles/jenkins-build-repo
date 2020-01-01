pipeline {
  agent any

  stages {
    stage('check') {
      steps {
        gradle(tasks: 'check')
      }
    }
    stage('test') {
      steps {
        gradle(tasks: 'test')
      }
    }
    stage('build') {
      steps {
        gradle(tasks: 'build')
      }
    }
  }
}