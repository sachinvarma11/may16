pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Hello\') {
            steps {
                echo \'Hello World\'
            }
        }
    }
}'''
        }
      }

    }
  }