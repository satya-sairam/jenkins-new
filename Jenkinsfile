pipeline{
    agent any 
    stages{
        stage("one"){
            steps{
                sh '''
                   echo "Hello world"
                '''
            }
        }
    

       stages{
        stage("two"){
            steps{
                sh '''
                   echo "Hello world -2"
                '''
            }
        }
    }
}
}