pipeline{
    agent{
        label{
            label "slave-1"
            customWorkspace "/root/vel-app"
        }
    }
    stages{
        stage("stage-1"){
            steps{
                sh "mkdir vel-appp"
            }
        }
        stage("stage-2"){
            steps{
                echo"hello"
            }
        }
    }
}
