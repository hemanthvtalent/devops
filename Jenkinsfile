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
            stage ('filecopy'){
                steps{
                    script {
                    'sh cp source/test.txt dest/
                    } 
                }
            }
    }
}