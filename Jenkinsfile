pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Karthikkl2001/pipline-me.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "java demo.java"
				}
			}
		}
	}
