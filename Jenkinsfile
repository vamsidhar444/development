pipeline {
  agent any
  stages {
    stage('stagging') {
      steps {
        build(job: 'my_pipeline', wait: true)
      }
    }

    stage('compile') {
      steps {
        sleep 12
      }
    }

  }
  environment {
    devops = '1'
  }
}