//Starter pipeline

pipeline {

    agent any

     stages {

        stage("Clone Repo") {
            steps {
                git "https://github.com/whatevershut/DEPLOYMENT"
            }
        }

        stage("Build") { 
            steps { 
                echo "Building"
            }
        }

        stage("Test"){
            steps {
                echo "Testing"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }
    }
}
