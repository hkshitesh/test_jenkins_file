pipeline{
    agent any
    stages{
        stage('CleanStage'){
          steps{
          echo 'Build Stage'
	      bat 'mvn clean'
          }
      }
      stage('BuildStage'){
          steps{
          bat 'mvn package'
          }
      }
    }
}
