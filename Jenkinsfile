pipeline{
  agent any

  stages{
    stage("clone git"){
      steps{ 
         git branch:'main',
         url: "https://github.com/VBharathirajA/sample_hosting"
      }
    }
    stage("build"){
      steps{
        bat "echo Build"
      }
    }
    stage("Run"){
      steps{
        bat "python second.py"
      }
    }
    stage("Test"){
      steps{
        bat "echo test"
      }
    }
  }
}
