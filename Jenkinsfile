node {
    
    stage('scm') {
    // some block
        git 'https://github.com/shaikkhajaibrahim/game-of-life.git'
    }
    
    stage('packaging'){
        sh 'mvn package'    
    }
 
stage ('archival') 
	//archiving artifact
	sh 'target/*.jar'
	}
}
