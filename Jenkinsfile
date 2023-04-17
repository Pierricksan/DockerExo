pipeline {
    agent any
    trigger {
        pollSCM('H/2 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

