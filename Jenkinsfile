pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
			  echo 'aedaedwedawede'
  
            }
            post {
                success {
                    echo 'Now Archiving...'
                    archiveArtifacts artifacts: '**/target/*.war'
                }
            }
        }
    }
}