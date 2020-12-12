node('build') {
  try {

    stage 'Build'
    node('build') {
        sh "sudo docker ps -a"
    }
  } catch(Exception e) {
    throw e
  }
}

