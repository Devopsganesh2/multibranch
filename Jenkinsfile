node('built-in') 
{
    stage('Continuous Download') 
	{
  git 'https://github.com/devopsganesh2/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
