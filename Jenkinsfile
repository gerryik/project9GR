pipeline{
  agent any
  stages{
    stage('project9'){
      parallel{     
        stage('Gerald Agbonye'){
          steps{
            sh '/var/lib/jenkins/project9grp5q1scrpit.sh'
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
