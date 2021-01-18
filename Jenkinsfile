pipeline {
    agent any
    stages {
        stage('pull package from git hub') {
            steps{
                //
				git credentialsId: '15610fd1-6d7e-4741-ae66-16e674d9f433', url: 'https://github.com/ccc43542876/CypressDemo.git'
            }
        }
         stage('run test cases') {
           steps{
			 bat 'npm run cy:verify'
             bat 'npm run cypress:run'
			 echo 'test'
           }
        }
         stage('clean Environment') {
           steps{
               echo 'clean'
           }
        }

    }
   
}
