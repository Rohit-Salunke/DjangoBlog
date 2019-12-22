pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'pylint --rcfile=pylint.cfg $(find . -maxdepth 1 -name "*.py" -print) MYMODULE/ > pylint.log || exit 0"'
            }
        }
    }
}