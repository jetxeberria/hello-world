node('docker') {
    checkout scm
    stage('Build') {
        docker.image('jetxeberria/astrodocker:latest').inside {
        // docker.image('python:3.5.1').inside {
            sh 'python --version'
            sh 'echo "Im a Jenkinsfile"'
            sh 'echo "Im the same Jenkinsfile"'
        }
    }
}

