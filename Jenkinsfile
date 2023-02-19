node('built-in') 
{
    stage('Continuous_loan_Download') 
	{
    git 'https://github.com/devopsganesh2/maven.git'
	}
    stage('Continuous_loan_Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
