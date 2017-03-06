/* Requires the Docker Pipeline plugin */
#node('remote') {
#    checkout scm
#    stage('Build') {
#        sh 'python --version'
#    }
#}

pipeline {
    agent { 'remote' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
