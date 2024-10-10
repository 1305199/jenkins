pipeline{
    agent{
        label{
            label "slave-1"

        }
    }
    stages{
        stage("stage-1"){
            steps{
                sh "mkdir vel-app"
            }
        }
        stage("stage-2"){
            steps{
                echo"hello"
            }
        }
    }
}
