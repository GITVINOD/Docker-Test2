node {
    checkout scm
    def testImage = docker.build("alpine:latest") 

    testImage.inside {
        sh 'make test'
    }
}
