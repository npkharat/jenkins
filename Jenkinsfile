pipeline {
	agent any


	stages{
		stage('Build'){
			steps{ echo "building the project"} 
		}

		stage('Deploy'){
			steps{echo "Deploying the project ..."}
		}

		stage("apt update"){
			steps{sh ''' sudo apt update ''' }
		}

		

		}
}

