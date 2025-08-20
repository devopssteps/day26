pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        //git 'https://github.com/devopssteps/day26.git'
        echo 'test'
      }
    }
    stage('Run Ansible') {
      steps {
        sh 'ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i hosts p1.yaml'
        }
    }
  }
}
