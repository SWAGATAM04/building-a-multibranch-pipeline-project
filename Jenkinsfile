node('build') {
  try {

    stage 'Build'
    node('build-run-on-this-node') {
        sh "sudo docker ps -a"
    }
  } catch(Exception e) {
    throw e
  }
}
