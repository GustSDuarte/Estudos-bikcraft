pipeline {
  agent any


  stages{
    stage('Clone Repository') {
            steps {
                git url: 'https://github.com/GustSDuarte/Estudos-bikcraft.git'
            }

    stage('Teste') {
        steps {
        sh 'docker --version'
      }
    }
  }
}