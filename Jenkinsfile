pipeline {
 agent { label 'agente1' }
  stages {
      stage('Build'){
          steps {
              sh '''
              echo "Hola"
              pwd
              uname
              docker ps
              echo "adios"
              mvn clean install
              '''
          }
      }
      stage('Test'){
          steps{
              echo "Do something"
          }
      }
      stage('Deploy'){
          steps{
              echo "Do something"
          }
      }
  }
}
