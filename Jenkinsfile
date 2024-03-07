pipeline {
    agent any
  stages {
    stage("Build") {
      steps {
        sh "chmod +x ./build.sh"
        sh "./build.sh"
      }
    }
    stage("test") {
        steps {
            sh "chmod +x ./test.sh"
            sh "./test.sh"
        }
    }
    stage("run") {
        steps {
            sh "chmod +x ./run.sh"
            sh "./run.sh"
        }
    }
  }
}
