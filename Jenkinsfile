pipeline{
    agent any{
        stages{
            stage('Build'){
                steps{
                    checkout scm
                }
            }
            stage('Test'){
                steps{
                    bat "python hello.py"
                }
            
            }
        }
    }
}