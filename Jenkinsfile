pipeline
{
  agent any
  stages
  {
    stage('Build')
    {
      agent 
      {
        label "build_server"
      }
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
