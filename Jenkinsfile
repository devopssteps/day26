pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        //git 'https://github.com/devopssteps/day26.git'
      }
    }
    stage('Run Ansible') {
      steps {
        sh 'ansible-playbook -i hosts p1.yaml'
      }
    }
  }
}
