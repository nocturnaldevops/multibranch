pipeline
{
    agent any
    stages
    {
        stage("contDownload")
        {
            steps
            {
                git branch: 'feature2', url: 'https://github.com/nocturnaldevops/multibranch.git'
            }
        }
        stage("contbuild")
        {
 steps{
            sh 'mvn package'
        }
}
}
}