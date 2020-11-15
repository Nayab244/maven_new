node('master') 
{
    stage('Continuos Download_Master') 
    {
    git 'https://github.com/Nayab244/maven.git'
    }
    stage('Continuos Build_Master') 
    {
    sh 'mvn package'
    }
}

