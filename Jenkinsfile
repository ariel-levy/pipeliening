pipeline {
    agent any
    stages {
    stage('GitHub Jenkins Ant Docker Build') {
      steps {
        sh 'ant clean compile test package war'
      }
    }
  }
}
