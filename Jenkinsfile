#!groovy

@Library('piper-lib-os') _

node() {
    stage('prepare') {
        checkout scm
        buildExecute script:this, buildTool: 'docker'
        echo "change 1"
    }
}
