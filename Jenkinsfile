pipeline {
    agent {
            docker { image 'centos:7' }
    }
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
