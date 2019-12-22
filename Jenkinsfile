pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'pylint test_project/polls > pylint.log || exit 0'
            }
        }
    }
}