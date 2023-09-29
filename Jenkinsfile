pipeline {
  agent any
  stages{
      stage("build"){
          steps{
              echo 'step 1'
              sleep 3
          }
      }
      stage("test"){
          steps{
              echo 'step 2'
              sleep 9
          }
      }
      stage("package"){
          steps{
              echo 'step 3'
              sleep 5
          }
      }
  }

  post{
    always{
        echo 'This pipeline is completed..'
    }
  }
}
