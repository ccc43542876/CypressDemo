pipeline {
    agent any
    stages {
        stage('build') {
            steps{
                 bat 'npm run cy:verify'
            }
        }
         stage('test') {
           steps{
             bat 'npm run cypress:run'
           }
        }
         stage('deploy') {
           steps{
               echo 'deploy'
           }
        }

    }
   
}
