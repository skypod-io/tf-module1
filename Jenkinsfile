pipeline {
    options {
        ansiColor('xterm')
        disableConcurrentBuilds()
        timeout(time: 1, unit: 'HOURS')
        timestamps()
    }
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Build'
                sh 'echo build'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Test'
                sh 'echo test'
            }
        }
    }
}
