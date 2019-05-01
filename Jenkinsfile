pipeline {

    agent any

    stages {

        stage('Setup') {
            steps {
                echo "Setup Stag"
            }
        }

        stage('Build') {
            steps {
                echo "Build Stag"
            }
        }

        stage('Release') {
            steps{
                echo "Release Stag"
            }
        }

        stage('Publication') {
            steps{
                sh 'printenv'
                echo "Publication Stag"
            }
        }
    }
}