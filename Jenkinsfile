pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                sh "git clone https://github.com/hlakhdari35/myrepo2.git"
            }
        }
        stage('run') {
            steps {
                sh "cd myrepo2/"
                sh "script1.sh"
            }
        }
        stage('fin') {
            steps {
                echo  "Fin de stages"
            }
}
}
}
