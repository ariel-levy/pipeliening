pipeline {
    agent any
    stages {
        stage('scm') {
            steps {
                checkout scm
            }
        }
        stage('build') {
            steps {
                echo 'Building...'
                sh 'echo BOOLDIING'
                git branch: 'main', url: 'https://github.com/ariel-levy/pipeliening.git'
            }
        }
    }
}
