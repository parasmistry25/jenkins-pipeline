pipeline {
  agent none
  stages {
    stage('Build'){
      steps {
        timeout(time: 1, unit: 'SECONDS') //DAYS,HOURS,MICROSECONDS,MINTES,NANOSECONDS,SECONS
        {
          echo "sleeping in timeout"
          sleep 3
        }
        
      }
    }
  }
}