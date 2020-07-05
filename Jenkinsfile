pipeline{
//to ran on any agent
  agent any
  stages{
      stages('build'){
        steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }  
      }
      stages('test'){
          steps {
          eco 'testing the application'
          }
      }
      stages('deploy'){
          steps {
          eco 'deploying the application'
          }
      }
  }
} 
