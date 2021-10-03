pipeline {
  agent any
  stages {
    stage('Dev Build') {
      steps {
        echo 'Maven build done locally'
        echo 'Unit tests executed'
      }
    }

    stage('Deploy to QA') {
      steps {
        echo 'Deploy to qa'
      }
    }

    stage('UI Testing (smoke)') {
      steps {
        echo 'ui tyesty'
      }
    }

    stage('Deploy to UAT') {
      steps {
        echo 'Deploy to UAT AWS'
        echo 'Notify UAT teams'
      }
    }

    stage('Certify UAT') {
      steps {
        echo 'certify'
      }
    }

    stage('Prod deplyment') {
      steps {
        echo 'Deploy to prod'
      }
    }

  }
}