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
             sh '''
              docker cp /home/devops/workspace/samanthaFolder/SamanthaPipeline/target/sparkjava-hello-world-1.0.war tomcat://usr/local/tomcat/webapps
             '''
          }
      }
  }
}
