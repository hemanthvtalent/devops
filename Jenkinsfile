pipeline {
    agent Node-one
        stages {
            stage ('Git') {
                steps{
                    script {
                    checkout scm
                    }
                }
            }
            stage ('report'){
                steps{
                    script {
                    echo "WELCOME"
                    } 
                }
            }
    }
}