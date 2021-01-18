pipeline {
    agent any
    stages {
        stage('build') {
            steps{
                //bat 'npm run cy:verify'
				git credentialsId: '15610fd1-6d7e-4741-ae66-16e674d9f433', url: 'https://github.com/ccc43542876/CypressDemo.git'
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
