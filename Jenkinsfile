pipeline {
	agent any
		
	stages {
		stage('Build') {
			steps {
				echo 'Building....'
				  }
					   }
		stage('Test') {
			steps {
					echo 'Testing..'
				  }
						}
		stage('Run My Script') {
			steps {
				sh('python test.py')
				  }
				               }
		stage('Deploy') {
			steps {
			 echo 'Deploying....'
			     }
				        }
			}
      }
