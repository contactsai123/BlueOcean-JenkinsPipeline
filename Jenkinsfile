pipeline {
  agent any
  stages {
    stage('print message') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Sai'
    TEST_USER = credentials('test-user')
  }
}