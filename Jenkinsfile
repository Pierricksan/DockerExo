pipeline {
    agent any
    triggers {
        pollSCM('H/2 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World a new update for a new test'
            }
        }
    }
}

