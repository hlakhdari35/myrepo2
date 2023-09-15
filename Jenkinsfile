pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/hlakhdari35/myrepo2.git"
            }
        }
        stage('run') {
            steps {
                sh "cd myrepo2/"
                sh "pwd"
            }
        }
        stage('fin') {
            steps {
                echo  "Fin de stages"
            }
}
}
}
