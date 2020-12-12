node (label: 'build'){
    stage('DockerContainer') {
        if (env.BRANCH_NAME == 'master') {
            docker ps -a
        } else {
            echo 'Please check branch'
        }
    }
}

