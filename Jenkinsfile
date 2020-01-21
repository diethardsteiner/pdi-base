pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('message') {
      steps {
        sh 'echo Pentaho version: ${PENTAHO_VERSION}'
      }
    }

  }
}