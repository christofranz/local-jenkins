pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'cd /home/chris/Dokumente/local-jenkins/my_file.py'
                sh 'ls'
            }
        }
    }
}
