pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                cd "/home/valeriy/eclipse-workspace/makefile_project/build/default"
                make -f ../../Makefile                
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
