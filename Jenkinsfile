pipeline {
  agent {
    docker {
      image 'node:8-alpine'
    }

  }
  stages {      
    stage('wellcome') {
      steps {
        sh 'echo "wellcome to dojo !"'
      }
    }
  }
  environment {
    npm_config_cache = 'npm-cache'
    HOME = '.'

  }
}