@Library('learn-jenkins-shared-library@main') _

import mim.jenkins.Output

pipeline {

    agent none
    
    stages {
        stage('Hello Groovy') {
            steps {
                script {
                    Output.hello('Groovy')
                }
            }
        }

        stage('Hello World') {
            steps {
                script {
                    hello.world()
                }
            }
        }
    }
}