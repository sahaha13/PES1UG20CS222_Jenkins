pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            steps
            {
                sh 'g++ hello.cpp'
                sh '/var/jenkins_home/workspace/pes1ug20cs222-1/main/hello_exec'
                echo 'Successful build'
            }
        }
        stage('Test')
        {
            steps
            {   
                sh './a.ouT'
                echo 'Output from c++ file is given'
            }
        }
        stage('Deploy')
        {
            steps
            {
                echo 'I am Deploying it now.....'
            }
        }
    }
}
