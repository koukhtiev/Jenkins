pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
//Building in: /home/valeriy/eclipse-workspace/makefile_project/build/default
                make -f /home/valeriy/eclipse-workspace/makefile_project/Makefile
                echo 'Building finished'            
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
