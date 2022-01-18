pipeline {
    agent any
    stages {
       stage('build') {
          steps {
             echo 'stage one'
          }
       }
       stage(test) {
           steps {
               echo 'stage two'
           }
       }
    }
 }




*/
node{
  stage("checkout"){
  git credentialsId: 'gitcredentials', url: 'https://github.com/bangloreorganizartion/java-hello-world-with-maven.git'
  }
}
/*
