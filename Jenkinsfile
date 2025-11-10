pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh pwd
                //sh "cd '/home/valeriy/eclipse-workspace/makefile_project/build/default'"
                //make -f '../../Makefile' 
                //make all
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
