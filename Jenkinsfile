pipeline {
  agent any
  stages {
    
    stage('Secrets Scan') {
      parallel {
        stage('Whipsers') {
          steps {
            echo 'hello, world!'
          }
        }
      }
    }
    
stage('SAST') {
      parallel {
    stage('Coverity') {
      steps {
        echo 'hello, world!'
      }
    }
      }
}

    stage('SCA') {
      parallel {
    stage('Snyk') {
      steps {
        echo 'hello, world!'
      }
    }
      }
    }
    

    stage('Container Scan') {
      parallel {
        stage('Trivy') {
          steps {
            echo 'hello, world!'
          }
        }

        stage('Snyk') {
          steps {
            echo 'hello, world!'
          }
        }

      }
    }

    stage('DAST') {
      parallel {
    stage('ZAP') {
      steps {
        echo 'hello, world!'
      }
    }
      }
    }

    stage('Compliance Scan') {
      parallel {
    stage('Inspec') {
      steps {
        echo 'hello, world!'
      }
    }
      }
    }

  }
}
