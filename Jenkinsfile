  
pipeline {
    agent {
        dockerfile true
    }
	stages{
    stage('Build-status') {
            steps {
                sh 'docker ps -a'
            }
    }
	}
}
