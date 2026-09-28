pipeline{
  agnet any
  stages{
    stage("Build"){
      steps{
        sh 'mvn -DskipTests clean package'
      }
      steps("Test"){
        sh 'mvn test'
      }
    }
  }
}
