pipeline {
  agent any
  stages {
    stage('get git url') {
      steps {
        echo 'Begin get stage'
        git(url: 'https://github.com/alexeykr65/jenkins_test.git', branch: 'master', poll: true)
        fileExists 'README.md'
      }
    }

    stage('Publish') {
      steps {
        sh '''echo \'all is ok\'


'''
      }
    }

  }
  environment {
    OSC_PASS = 'pass'
  }
}