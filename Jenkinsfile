pipeline 
	{
		agent any
		
			stages
			{
				stage('GIT CLONING')
				{
					steps
					{
							sh 'echo git clone '
					}
					
					
				}
				stage('Test')
				{
					steps
					{
							sh 'echo test'
					}
					
					
				}
				stage('Build Stage')
				{
					steps
					{
							sh 'echo build ho gya'
					}
					
					
				}
				stage('Get approval')
				{
					steps
					{
					input "Deploy to QA?"
					}
					
				}
				
				stage('Deploying')
				{
					steps
					{
							sh 'echo Deploying'
					}
					
					
				}
				}
			
	}
