pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git(url: 'https://github.com/p-vincen-t/jen-work.git', branch: 'main', poll: true)
      }
    }

  }
}
