pipeline {
    agent any
    trigger { 
        pollSCM('*/2 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

