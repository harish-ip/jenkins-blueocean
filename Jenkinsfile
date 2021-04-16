pipeline {
  agent any
  stages {
    stage('Building') {
      parallel {
        stage('Building') {
          steps {
            echo 'building'
          }
        }

        stage('Parallel build') {
          steps {
            echo 'Testing'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}