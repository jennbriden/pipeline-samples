pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        echo 'Hello World'
      }
    }
  }
  post {
    always {
      echo 'Hello World from post'
      script {
        def response = input message: 'Do you want to undeploy UAT environment?'
      }
      
      
    }
    
  }
}