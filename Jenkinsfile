pipeline {
  agent {
    node {
      label 'docker-jenkins'
    }
    
  }
  stages {
    stage('') {
      steps {
        git(url: 'git@github.com:practicaljenkins/python-project.git', branch: '*/master')
      }
    }
  }
}