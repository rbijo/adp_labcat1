pipeline{
    agent any{
        stages{
            stage('Build'){
                steps{
                    echo "Build"
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