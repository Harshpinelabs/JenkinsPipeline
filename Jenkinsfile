pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                //sh 'make' 
                echo 'Build sgate is up and running fine'
            }
        }
        stage('Test'){
            steps {
                //sh 'make check'
                //junit 'reports/**/*.xml' 
                echo 'Test sgate running fine'
            }
        }
        stage('Deploy') {
            steps {
                //sh 'make publish'
                echo 'Deploy sgate running fine'
            }
        }
    }
}
