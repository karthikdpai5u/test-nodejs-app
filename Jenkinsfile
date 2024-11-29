pipeline {
  agent any
  stages {
    stage('Install Dependencies') {
      steps {
        //sh 'sudo apt install npm -y'
        ech 'Install Dependencies'
      }
    }
    stage('Test') {
      steps {
        //sh 'npm --version"'
        echo 'Test Dependencies'
      }
    }
    stage("Deploy application") {
      steps {
        sh 'echo "deploying application..."'
      }
    }
  }
}
