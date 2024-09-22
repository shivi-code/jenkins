pipeline {
  agent any
  stages {
    stage('fetch the code') {
      steps {
        git(url: 'https://github.com/shivi-code/Ansilbe.git', branch: 'main ')
      }
    }

    stage('install apache') {
      steps {
        sh '''sudo apt install apache2 -y

'''
      }
    }

    stage('deploy application') {
      steps {
        sh 'sudo cp -R * /var/www/html/'
      }
    }

  }
}