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
}