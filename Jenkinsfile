pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''mvn -b clean compile
'''
      }
    }

    stage('test') {
      steps {
        sh 'mvn -b test'
      }
    }

  }
}