#!/usr/bin/env groovy
#!C:\Git\bin\bash.exe

pipeline {
  agent any
  tools {
  maven 'Maven 3.5.2'
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
