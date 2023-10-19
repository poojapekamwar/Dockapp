pipeline {
  agent any
  stages {
    stage('buildtstage') {
      steps {
        sh '''sudo docker login -u poojapekamwar -p Pooja@1525
sudo docker build -t poojapekamwar/myrepo2:${BUILD_NUMBER} .
sudo docker push poojapekamwar/myrepo2:${BUILD_NUMBER}'''
      }
    }

  }
}