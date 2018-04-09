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

        stage('prepare FW binary') {
          steps {
            sh 'echo \'start get the FW binary\''
            echo 'get the FW binary done'
          }
        }

        stage('prepare dump/trace') {
          steps {
            sh 'echo \'start get the FW binary\''
            echo 'get the FW binary done'
          }
        }

      }
    }

    stage('voice facities') {
      parallel{
        stage('CALL CONTROL COMMANDS') {
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
        stage('V25TER AT COMMANDS') {
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
        stage('AUDIO COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
      }
    }

    stage('data facities') {
      parallel{
        stage('DATA AT COMMANDS') {
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
        stage('PHONE BOOK MANAGEMENT') {
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
        stage('GPRS AT COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
      }
    }

    stage('supplementry facities') {
      parallel{
        stage('NETWORK SERVICE RELATED COMMANDS') {
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
        stage('SPECIFIC FLASH COMMANDS') {
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
      }
    }

    stage('IOT facities') {
      parallel{
        stage('AVMS COMMANDS') {
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
      }
    }

    stage('debug commands'){
      parallel{
        stage('NV COMMANDS') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
      }
    }

    stage('palletize') {
      parallel{
        stage('archiving binary') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
        stage('etch fingerprint') {
          steps {
            sh 'echo \'start build\''
            echo 'build done'
          }
        }
      }

    }
  }
}
