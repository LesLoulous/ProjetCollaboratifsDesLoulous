pipeline {
	agent any
	stages {
		stage('Checkout Github'){
			steps {
				git credentialsId: 'jenkins', url: 'https://github.com/LesLoulous/ProjetCollaboratifsDesLoulous.git'
			}
		}
		stage('Déploiement') {
			steps {
				sh 'rm -rf /var/www/html/client/*'
				sh 'cp -r ./ /var/www/html/client/'
				sh 'rm -rf /var/www/html/doc/*'
				sh 'cp -r ./doc/* /var/www/html/doc/'
			}
		}
	}

	post {
		success {
			echo 'Build&Deploy completed succesfully!'
		}
		failure {
			echo 'Build&Deploy failed. Check logs.'
		}
	}
}
