pipeline {
    agent {
        dockerfile true
    }
    stage('Build-status') {
            agent {
                docker { image 'alpine' }
            }
            steps {
                sh 'docker ps -a'
            }
    }
}
