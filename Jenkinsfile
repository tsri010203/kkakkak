node('built-in') 
{
    stage('Continuous Download_cards') 
	{
    git 'https://github.com/tsri01023/mycode.git'
	}
    stage('Continuous Build_cards') 
	{
    sh label: '', script: 'mvn package'
	}
}
