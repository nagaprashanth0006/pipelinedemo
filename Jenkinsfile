pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'sh /root/python_pipeline/tools/build_bottle.sh'
      }
    }
  }
}