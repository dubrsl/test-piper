#!groovy

@Library('piper-lib-os') _

node() {
    stage('prepare') {
        checkout scm
        mtaBuild script: this
    }
}