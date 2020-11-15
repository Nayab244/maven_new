node('master') 
{
    stage('Continuos Download_Loans') 
    {
    git 'https://github.com/Nayab244/maven.git'
    }
    stage('Continuos Build_Loans') 
    {
    sh 'mvn package'
    }
}

