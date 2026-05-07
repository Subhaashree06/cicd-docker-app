pipeline {

    agent any

    stages {

        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/Subhaashree06/cicd-docker-app.git'
            }
        }

        stage('Test Stage') {
            steps {
                echo "Pipeline Working Successfully"
            }
        }

        stage('Deploy Stage') {
            steps {
                echo "Application Deployment Successful"
            }
        }
    }
}
      
