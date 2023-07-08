pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'git clone https://github.com/jayesh271184/dhtechlab.git'
            }

          }
	    stage('shell') {
            steps {
                sh 'echo -e `hostname`-`date`'
            }

          }
    }
}
