#!/usr/bin/env groovy

pipeline {
  agent any
  stages {
    stage ('Stage 1') {
      steps {
        echo "Test started"
        }
      }
    stage ('build') {
      steps {
        sh 'mvn clear compile'
      }
    }
  }
}
