#!/usr/bin/env groovy

pipeline {
  agent any
  tools {
    maven 'Maven 3.5.0'
  }
  stages {
    stage ('Checkout') {
      steps {
        git https://github.com/Aionee855/Jenkins-test.git
        }
      }
    stage ('build') {
      steps {
        bat 'mvn clear compile'
      }
    }
  }
}
