pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
            echo 'Started'
            }
        }
        stage('Test'){
            when{
                expression{
                    return false
                }
            }
            steps{
                echo 'skipped'
            }
        }
        stage('Last'){
            steps{
                echo 'end'
            }
        }
    }
}
