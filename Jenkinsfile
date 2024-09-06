@Library('My-Jenkins-SharedLibrary') _

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Ensure that 'example-job' exists and can be triggered
                build job: 'example-job'
            }
        }
    }
}
