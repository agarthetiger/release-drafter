#!/usr/bin/env groovy
pipeline {
    agent any
    options {
        ansiColor('xterm')
        timestamps()
    }
    stages {
        stage('Dump env'){
            steps {
                sh 'env'
            }
        }
    }
}
