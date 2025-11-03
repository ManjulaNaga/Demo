pipeline{
  agent: any

  stages{
    stage("checkout"){
          steps{
            echo "cheeckout the git repo"
          }
    stage("build"){
      steps{
        echo "build the project"
      }
    }

    stage("test"){
          steps{
            echo "test the project"
          }
          }
    stage("deploy"){
      steps{
        echo "deploying the project"
      }
    }
    post{
      always{
        echo "pipeline finished"
      }
      success{
        echo "Pipeline successful"
      }
      failure{
        echo "Pipeline failed"
      }
    }
    }
  }
          
      
          
