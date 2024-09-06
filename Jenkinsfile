@Library('My-Jenkins-SharedLibrary') _

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Use the custom build method from the shared library
                build job: 'example-job',
                      parameters: [
                          string(name: 'PARAM1', value: 'value1'),
                          booleanParam(name: 'PARAM2', value: true)
                      ]
            }
        }
    }
}
