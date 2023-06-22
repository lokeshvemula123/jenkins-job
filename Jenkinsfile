pipeline {
   // agent {label 'dev'}
     agent any
    stages {
        stage('Buildd') {
            steps {
                echo 'Building.................'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
