pipeline {
    agent any
    environment {
        PATH="/usr/local/bin:$PATH"
    }
  
        stages {
            stage('terraform version') {
                steps {
                    sh "terraform -v"
                }
            }

        }
}
