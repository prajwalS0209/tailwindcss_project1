pipeline {
  agent any
  stages {
    stage('git checkout') {
      steps {
        git(url: 'https://github.com/prajwalS0209/tailwindcss_project1.git', branch: 'master')
      }
    }

    stage('bash scripting') {
      steps {
        sh '''ls -la
echo "its done" '''
      }
    }

  }
}