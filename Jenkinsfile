pipeline 
{
    agent any

    stages 
    {
        stage('Execute Cucumber Test Cases') 
        {
            steps 
            {
                bat 'docker-compose up'
            }
        }


        stage('Stop Execution') 
        {
            steps 
            {
                bat 'docker-compose down'
            }
        }
    }
}