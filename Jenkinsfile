pipeline {
    agent {
        dockerfile true
    }
	stages{
		stage('Build-status') {
            agent {
                docker { image 'alpine' }
				  }
            steps {
                sh 'docker ps -a'
				}
		}
    }
}
