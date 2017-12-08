
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
                build job: 'echo'
                parameters([string(name: 'name1', Value: 'nileshexperiments')])
            }
        }
    }
}
