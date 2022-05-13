pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh "chmod 777 check.sh"
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
