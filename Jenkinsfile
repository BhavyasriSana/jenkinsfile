@Library('shlib')_
pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Deploy') {
            steps {
                Build()
		    UserDetails(JSON)
		  //  testbuild()
            }
	}
    }
}
   

	
