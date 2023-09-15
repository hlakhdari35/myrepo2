pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
		sh  "rm -rf *"
		sh "git clone https://github.com/hlakhdari35/myrepo2.git"
		sh "sleep 10"
            }
        }
        stage('run') {
            steps {
                sh "cd myrepo2/myrepo2/"
		echo "use existinggit home"
                sh "pwd"
		sh "ls -l"
            }
        }
        stage('fin') {
            steps {
                sh "sh script1.sh"
            }
}
}
}
