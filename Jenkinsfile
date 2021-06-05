node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/Rajesh110692/Jenkins_multiBranch05.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}

}
