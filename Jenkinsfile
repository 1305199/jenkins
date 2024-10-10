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
                sh "chmod -R 777 /root/vel-app"
            }
        }
        stage("stage-2"){
            steps{
                echo"hello"
            }
        }
    }
}
