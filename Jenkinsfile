pipeline{

	agent any
	
	stages{
		
		stage('Build'){
			steps{
				sh 'echo build step 1'
				sh 'echo build step 2'
			}
		}
		
		stage('Test'){
                	steps{        sh 'echo Test step 4'
                        		sh 'echo Testing step 5'
                	}
		}
		stage('Deploy'){
                	steps{        sh 'echo deploy step 1'
                        	sh 'echo deploy step 2'
                	}
		}
	}
}


