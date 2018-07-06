pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'SQA-Blink-01', propagate: true)
      }
    }
  }
}