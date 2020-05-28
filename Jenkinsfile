pipeline {
  agent any
  stages {
    stage('Whipsers') {
      steps {
        echo 'hello, world!'
      }
    }

    stage('Coverity') {
      steps {
        echo 'hello, world!'
      }
    }

    stage('Snyk') {
      steps {
        echo 'hello, world!'
      }
    }

    stage('Container Scan') {
      parallel {
        stage('Trivy') {
          steps {
            sh 'hello, world!'
          }
        }

        stage('Snyk') {
          steps {
            echo 'hello, world!'
          }
        }

      }
    }

    stage('ZAP') {
      steps {
        echo 'hello, world!'
      }
    }

    stage('Inspec') {
      steps {
        echo 'hello, world!'
      }
    }

  }
}