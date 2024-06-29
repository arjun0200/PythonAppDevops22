pipeline
{
agent{
  label "ec2"
}
  stages{
    stage("Deployment on PROD Env"){
      steps{
        sh "docker run -dit --name webos -p 80:80 jinny1/gfg22cicd"
      }
    }
  }
}
