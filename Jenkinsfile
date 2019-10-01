pipeline {
    agent any
    environment {
          PATH= "/usr/local/bin/terraform:${PATH}"
        }
   
        stages {
            stage('terraform version') {
                steps {
                    sh "terraform -v"
                }
            }

        }
}
