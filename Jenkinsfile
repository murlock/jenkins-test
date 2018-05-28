pipeline {
    agent {
            docker { image 'centos:7' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'id -u'
                sh 'sudo yum install gcc'
                sh 'gcc -o hello.x hello.c'
                sh './hello.x'
            }
        }
    }
}
