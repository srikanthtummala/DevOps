pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/srikanthtummala/DevOps.git', branch: 'master', changelog: true)
      }
    }
  }
}