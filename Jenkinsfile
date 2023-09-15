pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
		echo "use existinggit home"
            }
        }
        stage('run') {
            steps {
                sh "cd myrepo2/"
                sh "pwd"
		sh "ls -l"
            }
        }
        stage('fin') {
            steps {
                echo  "Fin de stages"
            }
}
}
}
