pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/kishorekk12/DevopsDemo.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        sh 'mvn install'
      }
    }

  }
}