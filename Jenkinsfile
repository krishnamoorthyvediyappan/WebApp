pipeline {
  agent any
  stages {
    stage('Dev Code Pull') {
      steps {
        echo 'Unit tests executed'
      }
    }

    stage('Dev Maven Build') {
      steps {
        echo 'Dev Maven Build'
      }
    }

    stage('QA Deploy') {
      steps {
        echo 'Deploy to QA'
      }
    }

    stage('QA Tests') {
      steps {
        echo 'Web code pull and run test'
        echo 'API code pull and run test'
      }
    }

    stage('QA Certification') {
      steps {
        echo 'Certify qa manually'
        input 'Do you wish to certify?'
      }
    }

    stage('UAT Deploy') {
      steps {
        echo 'Deploy to UAT'
      }
    }

    stage('UAT Certification') {
      steps {
        input 'Do you wish to certify ?'
      }
    }

    stage('Prod Deploy') {
      steps {
        echo 'Deploy to prod'
      }
    }

  }
}