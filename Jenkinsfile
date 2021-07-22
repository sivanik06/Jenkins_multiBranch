node('master') 
{
    stage('ContinuousDownload_master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_master') 
	{
    sh label: '', script: 'mvn package'
	}

}
