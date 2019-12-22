pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                cd /Users/ben/PycharmProjects/DjangoBlog
                pylint test_project/polls
                '''
            }
        }
    }
}