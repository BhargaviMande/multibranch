node{
    stage('Continuous Download') 
	{
    git 'https://github.com/BhargaviMande/maven-1.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
        }
}
