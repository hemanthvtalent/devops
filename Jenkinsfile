pipeline {
    agent [ Node1 ]
        stages {
            stage('Git') {
                steps{
                    script {
                    checkout scm
                    }
                }
            }
            stage ('report'){
                steps{
                    script {
                    echo "WeeeeeeelCOME"
                    } 
                }
            }
       }
}