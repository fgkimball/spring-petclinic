pipeline {
  agent any
  tools {
    maven "the_maven"
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
