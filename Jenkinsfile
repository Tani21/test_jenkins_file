pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('Test'){
          steps{
          bat 'mvn clean'
          }         
      }
        stage('Stage 3'){
          steps{
         echo 'Stage 3'
          }         
      }
        stage('Stage 4'){
          steps{
         echo 'Stage4'
          }         
      }
      stage('Name of stage')
      {
      steps{
      	echo "whatever you want the stage to do"
      }

    }
}
