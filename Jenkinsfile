pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build :!!*'
      }
    }

    stage('test stage') {
      parallel {
        stage('test 1') {
          steps {
            echo 'tes1'
          }
        }

        stage('test2') {
          steps {
            echo 'test2'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}