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
        sh "mvn test"
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
