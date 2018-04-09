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
        stage('GPRS AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('SIM APPLICATION TOOLKIT AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('AUDIO COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('PROTOCOL SPECIFIC COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('SPECIFIC FLASH COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('ECALL COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('DSDS COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('LOCATION SERVICE COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('V25TER AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('NV COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('M2M SERVICE OPTIMIZATION COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('GENERAL AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('CALL CONTROL COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('MOBILE EQUIPMENT CONTROL AND STATUS COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('NETWORK SERVICE RELATED COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('PHONE BOOK MANAGEMENT') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('SMS AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('DATA AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
      }
    }
    stage('IOT commands/functionaires') {
      parallel{
        stage('AVMS COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
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
