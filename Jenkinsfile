pipeline {
    agent any

    stages {
        stage('Checkout Repo') {
            steps {
                git branch: 'master', url: 'git@github.com:Mayisha321/Ostad-Module2_Project2.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        
        stage('Read File') {
            steps {
                echo 'Reading hello.txt content...'
                sh 'cat hello.txt'
            }
        }

    }
}
