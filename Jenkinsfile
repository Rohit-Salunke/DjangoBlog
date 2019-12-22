pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                cd $WORKSPACE
                pylint test_project/polls > pylint.log || exit 0
                '''
            }
        }
    }
}