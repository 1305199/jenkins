pipeline{
    agent{
        label{
            label "built-in"
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
