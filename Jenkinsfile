pipeline{
  agent any
   tools {
        maven "Maver3.8"
        jdk "JDK 1.8"
        
    }
  stages{
    stage("Build"){
      steps{
        bat "mvn clean compile"
        echo "Building the project"
      }
    }
     stage("Test"){
      steps{
        echo "Testing the project"
      }
    }
     stage("Deploy"){
      steps{
        echo "Deploying the project"
      }
    }
  }
}

