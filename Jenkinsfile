pipeline {
  agent any
  stages {
    stage('clone repo') {
      steps {
        git(url: 'https://github.com/oomgomgxx/docker-plugin-demo.git', branch: 'main')
      }
    }

    stage('compile') {
      steps {
        sh 'mvn -v'
      }
    }

  }
}