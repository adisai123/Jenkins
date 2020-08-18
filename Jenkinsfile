pipeline {
  stages {
    stage('print') {
      parallel {
        stage('print') {
          steps {
            echo 'hiii'
            echo 'hii'
          }
        }

        stage('pr') {
          steps {
            echo 'print "${aditya}"'
          }
        }

      }
    }

  }
  environment {
    aditya = 'aditya'
  }
}