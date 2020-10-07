pipeline {

    agent any
    
    stages {

        stage("Build") {

            steps {

                echo 'Starting Build'
            }
        }
        stage("Test") {

            steps {
                echo 'Staring test'
            }
        }
        stage("Deploy") {
            
            steps {
                echo 'Test successful, will deploy'
		echo 'Minor change for PR'
            }
        }
    }
}
