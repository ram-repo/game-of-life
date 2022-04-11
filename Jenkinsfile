
pipeline{
  agent any
  stages{
    stage('chekout'){
      steps{
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ram-repo/game-of-life.git']]])
      }
    }
  }
}
