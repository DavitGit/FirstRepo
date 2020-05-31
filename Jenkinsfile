pipeline {
  agent {
    docker {
      image 'a'
      args 'aa'
    }

  }
  stages {
    stage('') {
      steps {
        echo 'heyy'
      }
    }

    stage('buinding') {
      steps {
        build(job: 'first', wait: true, quietPeriod: 2)
      }
    }

  }
  environment {
    aaa = 'dddd'
  }
}