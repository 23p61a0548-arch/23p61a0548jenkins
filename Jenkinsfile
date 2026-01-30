pipeline
{
    agent any 
    stages
    {
        stage("clone")
        {
            steps
            {
                git branch:'main',url:'https://github.com/23p61a0548-arch/23p61a0548jenkins.git'
            }
        }
        stage('build')
        {
            steps
            {
                sh "javac Hello.java"
            }
        }
stage('run')
{
    steps
    {
        sh 'java Hello'
    }
}
    }
}
