pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'pylint --rcfile=pylint.cfg $(find . -maxdepth 1 -name "*.py" -print) test_project/ > pylint.log || exit 0'
            }
        }
    }
}