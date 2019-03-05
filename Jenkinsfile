#!/usr/bin/env groovy
@Library(['jenkins-library']) _

node{
stage ("Git Clone.."){
    checkout scm
    }
stage("Building the Application") {
    sh 'cd spring-petclinic'
    sh './mvnw spring-boot:run'
    }
}
