pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''pipeline{
        agent any
        stages{
                stage(\'build\'){
                        steps{
                               sh \'echo build\'
                        }
                }
                stage(\'test\'){
                        steps{
                               sh \'echo test\'
                        }
                }
                stage(\'deploy\'){
                        steps{    
                               sh \'echo deploy\'
                        }
                }
}


}    '''
        }
      }

    }
  }