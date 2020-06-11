pipeline {
  agent { label 'docker' }
  stages {
    stage('build') {
      steps {
        sh 'python -u /home/chris/Dokumente/local-jenkins/my_file.py'
      }
    }
  }
}
