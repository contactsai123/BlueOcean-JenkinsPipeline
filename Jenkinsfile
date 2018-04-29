pipeline {
  agent any
  stages {
    stage('print message') {
      steps {
        echo "Hello ${MY_NAME} ${params.Name}!"
      }
    }
  }
  environment {
    MY_NAME = 'Sai'
  }
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}