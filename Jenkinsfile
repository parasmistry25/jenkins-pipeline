pipeline {
  agent none
  stages {
    stage('Build'){
      steps {
        retry(3) {
          echo "before throwing errro"
          error "error in retry"
        }
        echo "after retry (3)"              
      }
    }
  }
}