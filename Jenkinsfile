pipleline {
 agent any
 stages {
  stage ('Build') {
   steps {
    echo 'Building Automation'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    
   }
   }
   }
   }
 
 
