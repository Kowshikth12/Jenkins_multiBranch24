node('built-in') 
{
    stage('ContinuousDownload_mater') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_maste:r') 
	{
    sh label: '', script: 'mvn package'
	}
}
