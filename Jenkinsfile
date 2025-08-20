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
        sshagent(['26A']) {
            sh 'ansible-playbook -i hosts p1.yaml'
        }  
      }
    }
  }
}
