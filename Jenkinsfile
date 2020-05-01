pipeline {
  agent any
  stages {
    stage('Build simple api Dockerfile and app image') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Deploy infrastructure with Ansible') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Testing image') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Run simple api container') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Testing the api') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Validate image with Clair') {
      steps {
        echo 'Hello world'
      }
    }
    stage('push images to registry server') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Run security testing with Arachni') {
      steps {
        echo 'Hello world'
      }
    }
  }
  post{
      always{
        echo 'delete working directory'
        deleteDir()
        sh 'ls -la'
        echo 'checkout the project'
        checkout scm
        sh 'ls -la'
      }
      success{
        echo "====++++Successfully deployed++++===="
      }
  }
}