#!/usr/bin/env groovy

node {
  stage('stage 1') {
    echo "Hello World"
  }
  stage('stage 2') {
    echo "We are at stage 2"
  }
  stage('Say Hello') {
    if (isUnix()) {
    sh "./sayHello.sh"
    } else {
    bat "sayHello.cmd"
    }
  }
}
