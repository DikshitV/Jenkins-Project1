pipeline
{
  agent any
  stages
  {
    stage('Build')
    {
      steps
      {
        echo 'Build App'
          sh "mvn clean"
          sh "mvn compile"
      }
    }
     stage('Test')
    {
      steps
      {
        echo 'Test App'
      }
    }
     stage('Deploy')
    {
      steps
      {
        echo 'Deploy App'
      }
    }
  }
}
