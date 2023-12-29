node {
    stage('Build') {
        docker.image('node:latest').inside {
            sh 'npm install'
        }
    }
    stage('Test') {
        sh './jenkins/scripts/test.sh'
    }
}
