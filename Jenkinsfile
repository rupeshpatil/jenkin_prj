pipeline {
  agent any
  options{
    timestamps()
    ansiColor("xterm")
  }
  stages {
    stage("build"){
      options{
          timeout(time:1 , unit:"SECONDS")
      }
      steps{
          echo "building the application"
      }
    }
    stage("test"){
      steps{
          echo "testing the application"
      }
    }
    stage("deploy"){
      steps{
          echo "deploying the application"
      }
    }
  }
}
