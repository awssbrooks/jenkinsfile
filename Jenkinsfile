pipeline {

    agent any
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'constructing the application...'
            }
        }
         stages {
         
        stage("test") {
        
            steps {
                 echo 'testing if construction was done properly...'
            }
        }
         stages {
         
        stage("deploy") {
        
            steps {
                 echo 'deploying the newly constructed application...'

            }
        }
    }
}
