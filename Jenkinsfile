pipeline {
	    agent{
            docker{
                image "python:3.8"
                args "-u root:root"
            }
        }
	    stages {
	        stage('instalando requisitos'){
	            steps{
	                echo "requisitos"
                    sh "pip install -r requisitos.txt"
	            }
	        }
	        stage('STAGE 01'){
	            steps{
	                echo "Pipeline Usando Jenkinsfile"
	            }
	        }
	    }
	} 