pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                  pwd
                  ls -l
                  cat f
                  mvn --version
                '''
            }
        }
    }
}
