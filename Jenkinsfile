pipeline {
  agent {
    node {
      label 'linux'
    }
  }
  stages {
    stage('Build') {
      node('linux') {
        sh 'sh /root/python_pipeline/tools/build_bottle.sh'
      }
    }
  }
}
