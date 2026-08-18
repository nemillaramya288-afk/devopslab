pipeline {
  agent any
  stages {
    stages ('compile') {
      steps {
        sh 'python3 helloworld.py'
      }
    }
    stages ('run') {
      steps {
        sh 'python helloworld'
      }
    }
  }
}
