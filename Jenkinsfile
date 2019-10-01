pipeline {
    agent none 
    stages {
        stage('terraform version') {
            steps {
                echo 'Terraform version is displayed below'
                sh 'terraform -v'
            }
        }
        stage('View Terraform Help Command') {
            steps {
                echo 'View Terraform Help Command Below'
                sh 'terraform'
            }
        }
    }
}
