node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Rajesh110692/Jenkins_multiBranch05.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}

}
