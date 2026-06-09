pipeline {
    agent {
        label any
    }

    options {
        buildDiscarder(logRotator(numToKeepStr: '5'))
        disableConcurrentBuilds()
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
            }
        }
    }
}