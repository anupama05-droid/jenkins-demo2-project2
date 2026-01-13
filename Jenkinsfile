pipeline {
    agent any
    stages 
    {

        stage('Build') 
        {
            steps 
            {
                echo 'Building the application'
                sh 'ls -l'
            }
        }

        stage('Prepare') 
        {
            steps 
            {
                echo 'Preparing the application'
            }
        }
        
        stage('Test') 
        {
            steps 
            {
                echo 'Testing the application'
                sh 'bash test.sh'
            }
        }
        
        stage('Deploy') 
        {
            steps 
            {
                echo 'Deployiing the appication'
                sh 'echo  "Website CI pipeline executed successfully!"'
            }
        }

    
    }
}
