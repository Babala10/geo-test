pipeline{
    agent any
    stage {
        stage('hello'){
              steps{
                sh 'echo hello'
              }
        
        }
        stage(clean artifact){
            steps{
                sh 'echo hi'
            }
        }
      

    }
}