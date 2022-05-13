pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh "./check.sh"
                
            }
        }
        stage("test"){
            steps{
                echo "tesing done"
            }
        }
    }
}
