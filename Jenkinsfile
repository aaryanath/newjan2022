node('master_lab') 
{
    stage('Continuous Download_test') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_test') 
	{
    sh 'mvn package'
	}
}
