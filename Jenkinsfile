/* Requires the Docker Pipeline plugin */
node('remote') {
    checkout scm
    stage('Build') {
        docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
        }
    }
}
