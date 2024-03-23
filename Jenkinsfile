pipeline {
  agent none
  stages {
    stage('Build'){
      steps {
        retry(3) {
          echo "before throwing errro"
          errro "error in retry"
        }              
      }
    }
  }
}