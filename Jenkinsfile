pipeline{
        agent any
        stages{
            stage('Clone Repo'){
                steps{
                    checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://gitlab.com/qacdevops/chaperootodo_client']]])
                }
            }
        }    
}
