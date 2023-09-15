pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
	        sh "rm -rf *"
                sh "git clone https://github.com/hlakhdari35/myrepo2.git"
            }
        }
        stage('ru script') {
            steps {
                sh "cd myrepo2/"
		sh "script1.sh"
            }
	stage('ru fin') {
            steps {
                echo  "Fin de stages"
            }
			}
			
}
}
}
