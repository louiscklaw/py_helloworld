pipeline {
  agent any
  stages {
    stage('build') {
      parallel{
        stage('prepare test setup') {
          steps {
            sh 'echo \'start prepare test setup\''
            echo 'prepare test setup done'
          }
        }
        stage('get the FW binary') {
          steps {
            sh 'echo \'start get the FW binary\''
            echo 'get the FW binary done'
          }
        }
      }
    }
    stage('test') {
      parallel {
        stage('functional') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('test1') {
          steps {
            echo 'helloworld'
          }
        }
      }
    }
    stage('deploy') {
      steps {
        sh 'echo \'start build\''
        echo 'build done'
      }
    }
  }
}
