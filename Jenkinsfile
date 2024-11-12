   pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Checks Python version
      }
    }
    stage('hello') {
      steps {
        bat 'C:\Users\Lenovo\AppData\Local\Programs\Python\Python39\python.exe p1.py' 
      }
    }
  }
}
