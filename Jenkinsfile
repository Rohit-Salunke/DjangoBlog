pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                pylint --rcfile pylint.cfg test_project/polls
                '''
            }
        }
    }
}