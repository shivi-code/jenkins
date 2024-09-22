pipeline {
  agent any
  stages {
    stage('fetch code') {
      steps {
        git(url: 'https://github.com/shivi-code/jenkins.git', branch: 'main')
      }
    }

  }
}