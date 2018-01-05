#!/usr/bin/env groovy


pipeline {
  agent any
  tools {
  maven 'Maven 3.5.0'
  }
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
