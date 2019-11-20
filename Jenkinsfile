pipeline {
  environment {
   WORKSPACE='C:\Users\Junhui\.jenkins\workspace\My_Pipeline_master\'
  }
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
