pipeline {
  agent {label 'test'}
  stages {
    stage('build') {
      steps {
        sh 'echo Building ${BRANCH_NAME}...'
      }
    }
  }
}
