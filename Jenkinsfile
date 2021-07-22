node('master') 
{
    stage('ContinuousDownload_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
