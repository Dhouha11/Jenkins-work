pipeline {

    agent any
    stages {

        stage("build") {
            when {
                expression {
                    BRANCH_NAME == 'Dhouha11-version-1'
                }
            }
            steps {
                echo ' building the application..'
            }
        }
        stage("test") {
            when {
                expression {
                    BRANCH_NAME == 'Dhouha11-version-1'
                }
            }
            steps {
                echo ' testing the application..'
            }
        }
        stage("deploy") {
            steps {
                echo ' deploying the application..'
            }
        }
        post {
            success {
                echo ' You did it ..'
            }
        }   
    }
}
