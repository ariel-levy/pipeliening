pipeline {
    agent any
    stages {
    stage('GitHub Jenkins Ant Docker Build') {
      steps {
        git 'https://github.com/ariel-levy/pipeliening.git'
        sh 'ant clean compile test package war'
      }
    }
  }
}
