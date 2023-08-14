node {
    stage('Build') {
        docker.image('node:16-buster-slim').inside('-p 3200:3200') {
            sh 'npm install'
        }
    }
}