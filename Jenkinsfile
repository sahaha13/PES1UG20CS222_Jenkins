pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            steps
            {
                sh 'g++ pes1ug20cs222.cpp'
                sh '/var/jenkins_home/workspace/pes1ug20cs222-1/main/hello_exec'
                echo 'Build Stage Successful'
            }
        }
        stage('Test')
        {
            steps
            {   
                sh './a.ouT'
                echo 'Output from cpp file'
            }
        }
        stage('Deploy')
        {
            steps
            {
                echo 'Deploying...'
            }
        }
    }
}
