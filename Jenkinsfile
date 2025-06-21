pipeline {
    agent any 


    stages {
        stage('clone repo') {
            steps {
                 git branch: 'main', credentialsId: 'jenkins-gitub-4-u', url: 'git@github.com:AryanRawwat/DevOps-Assignment_practice-4-u.git'

            }
        }
   }
}
