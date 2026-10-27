pipeline{
  agent any

  stages{
    stage("build"){
      steps{
        bat "echo Build"
      }
    }
    stage("Run"){
      steps{
        bat "python index.py"
      }
    }
    stage("Test"){
      steps{
        bat "echo test"
      }
    }
  }
}
