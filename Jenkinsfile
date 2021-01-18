pipeline {
    agent any
    stages {
        stage('build') {
            steps{
                //bat 'npm run cy:verify'
				echo 'build...'
            }
        }
         stage('test') {
           steps{
             //bat 'npm run cypress:run'
			 echo 'test'
           }
        }
         stage('deploy') {
           steps{
               echo 'deploy'
           }
        }

    }
   
}
