pipeline{
  agent any
  stages{
    stage('project9'){
      parallel{     
        stage('Gerald Agbonye'){
          steps{
            sh 'bash x /var/lib/jenkins/workspace/ec2ststscrpit.sh'
          }
        }
        stage('Pretei Lemo'){
          steps{
            echo "actions2"
          }
        }
      }
    }
    stage('Odile Domingo'){
    	steps{
    		echo "echo codebuild stage"
    	}
    }
  }
}
