pipeline {
  agent any
  stages {
    stage('Initialisation') {
      parallel {
        stage('Initialisation') {
          steps {
            sh '''echo "Demarrage du pipeline"

'''
          }
        }

        stage('') {
          steps {
            sh '''echo "Demarrage du pipeline"
'''
          }
        }

      }
    }

    stage('Verification systeme') {
      parallel {
        stage('Verification systeme') {
          steps {
            sh 'uname -a'
            sh 'java -version'
            sh 'mvn -version'
          }
        }

        stage('') {
          steps {
            sh 'uname -a'
            sh 'java -version'
            sh 'mvn -version'
          }
        }

      }
    }

    stage('Test script') {
      parallel {
        stage('Test script') {
          steps {
            sh 'echo "Hello from Jenkins!"'
            sh 'echo "Pipeline execution successful"'
          }
        }

        stage('') {
          steps {
            sh 'echo "Hello from Jenkins!"'
            sh 'echo "Pipeline execution successful"'
          }
        }

      }
    }

  }
}