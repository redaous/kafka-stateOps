pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          echo 'Stage 1'
        }
      }
    }
    
    if (env.BRANCH_NAME == 'master') { 
             stage('Stage 2') {
                 steps {
                  script {
                    echo 'Stage 2'
                  }
                 }
                 }
    }
  }
}
