 pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                
                echo 'Build sgate is up and running fine'
            }
        }
        stage('Test'){
            steps {
                 
                echo 'Test sgate running fine'
            }
        }
        stage('Deploy') {
            steps {
                
                echo 'Deploy sgate running fine'
            }
        }
    }
}
