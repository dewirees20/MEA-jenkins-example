pipeline {
    agent any
  stages {
    stage("run shell script") {
      steps {
        sh "chmod +x ./example.sh"
        sh "./example.sh"
      }
    }
  }
}
