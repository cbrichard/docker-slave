pipeline {
    agent any

    stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }

    stage('Build Image') {
        sh('docker build -f Dockerfile')
    }
}
