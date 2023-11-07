pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                git 'https://github.com/ariel-levy/pipeliening.git'
            }
        }
    }
}
