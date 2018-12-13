pipeline{
  node('linux') {
    stage('build') {
      steps{
        sh /root/python_pipeline/tools/build_bottle.sh
      }
    }
  }
}
