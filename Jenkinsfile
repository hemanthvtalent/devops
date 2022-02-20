pipeline {
    agent { label 'node1' }
        stages {
            stage ('Git') {
                steps{
                    script {
                    checkout scm
                    }
                }
            }
            stage ('FS'){
                steps{
                    script {
                    sh "rm -rf source"
                    sh "rm -rf dest"
                    } 
                }
            }
    }
}