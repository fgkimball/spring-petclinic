pipeline {
  agent any
  tools {
    the_maven "Maven 3.1.2"
    jdk "jdk8"
  }
  stages{
    stage('Build'){
      steps{
        sh 'mvn -Dmaven.test.failure.ignore=true install'
      }
    }
  }
}
