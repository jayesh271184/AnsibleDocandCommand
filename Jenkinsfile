pipeline {
  agent any
  stages {
    stage('gitStage') {
        steps {
            git 'https://github.com/jayesh271184/dhtechlab.git'
          }
       }

    stage('Stage2') {
      steps {
        sh 'echo "Hello jayesh"'
      }
    }

  }
}
