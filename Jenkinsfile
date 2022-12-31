pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                sh ''''
                    docker version
                    docker info
                '''
            }
        }

        stage("test") {
            steps {
                echo 'testing the application...'
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying the application...'
            }
        }
    }
}
