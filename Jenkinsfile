pipeline {
  stages {
    stage('check') {
      steps {
        gradle('check')
      }
    }
    stage('test') {
      steps {
        gradle('test')
      }
    }
    stage('build') {
      steps {
        gradle('build')
      }
    }
  }
}