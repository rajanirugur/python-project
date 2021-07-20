pipeline {
  agent {
    node {
      label 'docker-jenkins'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/rajanirugur/python-project.git', branch: 'master')
      }
    }
    stage('build') {
      steps {
        sh 'python *test.py'
      }
    }
  }
}
