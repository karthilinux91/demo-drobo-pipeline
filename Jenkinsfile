pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'SQA-Blink-01', propagate: true)
      }
    }
  }
  environment {
    drobosn = 'DRB124701A00083'
    number = '1'
  }
}