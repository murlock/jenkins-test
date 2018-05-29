pipeline {
    agent {
            dockerfile true
    }
    stages {
        stage('Build') {
            steps {
                sh 'id -u'
                sh 'gcc -o hello.x hello.c'
                sh './hello.x'
            }
        }
    }
}
