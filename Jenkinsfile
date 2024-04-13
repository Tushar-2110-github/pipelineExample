pipeline{
    agent any
    stages {
        stage("compile"){
           steps{
             bat 'javac hy.java'
           }
        }
        stage("run"){
            steps{
                bat "java hy"
            }

        }
    }

    post{

            always{
                bat 'echo "always"'
            }

            success{
                bat 'echo "Success"'
            }

            failure{
                bat 'echo"failure"'
            }
        }
}