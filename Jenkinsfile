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
        //sh 'ansible-playbook -i hosts p1.yaml'
        sh 'ansible-playbook -i /home/ubuntu/33/26/hosts /home/ubuntu/33/26/p1.yaml'
      }
    }
  }
}
