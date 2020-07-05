pipeline{
//to ran on any agent
  agent any
  stages{
      stage("build"){
        steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }  
      }
      stage("test"){
          steps {
          eco 'testing the application'
          }
      }
      stage("deploy"){
          steps {
          eco 'deploying the application'
          }
      }
  }
} 
