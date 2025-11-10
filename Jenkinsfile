pipeline {
    agent any

        stages {
           stage('Show Files') {
                environment {
              MY_FILES = sh(script: 'cd mydir && ls -l', returnStdout: true)
            }
            steps {
                echo "$MY_FILES"
            }
        }
        stage('Build') {      
            steps {
                echo 'Building..'
                //sh pwd
                //CUR_LOCATION = sh pwd
                //sh "cd '/home/valeriy/eclipse-workspace/makefile_project/build/default'"
                //make -f '../../Makefile' 
                //make all
                //echo 'Building finished $(CUR_LOCATION)'            
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
