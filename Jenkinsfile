pipeline {
    agent {docker {images 'ubuntu'}}
    stages {
      stages('Build') {
          steps{
              sh 'docker images'
          }
        }
    }
}

