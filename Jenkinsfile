pipeline {
 agent { label 'samantha' }
  stages {
      stage('Build'){
          steps {
              sh '''
              echo "Hola"
              pwd
              uname
              docker ps
              echo "adios"
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
