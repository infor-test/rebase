pipeline {
    agent { label 'demo'
	}
	
	stages {
	    stage ('1') {
		   steps {
		      git credentialsId: '3d544f37-c71f-4f0f-9e84-c60e24f53cce', url: 'https://github.com/infor-test/demo.git'
		   }
		}
		stage ('2') {
		    steps {
			    echo "hello welcome"
				}
		}		
	}
}
