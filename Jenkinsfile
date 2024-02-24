pipeline
	{
	agent any
		stages
			{
			stage("GIT")
				{
				steps
					{
					git "https://github.com/Challavenkateswarlu/jenkins.git"
					}
				}
			stage("Run")
				{
				steps
					{
					sh "python3 main.py"
					sh "java Demo.java"
					}
				}
			}
	}
