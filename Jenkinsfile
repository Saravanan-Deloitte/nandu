pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Checkout') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage('ApprovalForDev') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage(' Dev stage') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage('ApprovalForQA') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage(' QA Stage') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'echo saravanakumar'
      }
        }
      stage('ApprovalForUAT') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'echo saravanakumar'
        sh 'printenv'
      }
        }
      stage('UAT stage') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage('ApprovalForProd') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
      stage('Prod Stage') {
      steps {
        sh "echo building $BRANCH_NAME"
        sh 'printenv'
        sh 'echo saravanakumar'
      }
        }
    }
    post {
    success {
      echo " $BRANCH_NAME build is succeeded!"
    }
    failure {
      echo " $BRANCH_NAME build is failed"
    }
    }
}
