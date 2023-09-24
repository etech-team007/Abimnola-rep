pipeline{
	agent any 
		stages{
			steps('1-clonecode'){
				steps{
					sh 'checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'team7 git-id', url: 'https://github.com/etech-team007/Abimnola-rep.git']])'
				}
			}
			stage('2-artifactbuild'){
				steps{
					sh 'df-h'
				}
			}
			stage('3-unitest'){
				steps{
					sh 'lscpu'
				}
			}
		}
	