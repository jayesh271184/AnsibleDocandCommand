pipeline {
  agent any
  stages {
    stage('gitStage') {
      parallel {
        stage('gitStage') {
          steps {
            git 'https://github.com/jayesh271184/dhtechlab.git'
          }
        }

        stage('Stage') {
          steps {
            sh 'echo `hostname`-`date` > /tmp/test.csv'
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "Hello jayesh"'
      }
    }

  }
}
