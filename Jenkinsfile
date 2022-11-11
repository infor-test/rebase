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
		stage ('file-download') {
			steps {
				script {
				sh 'wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.68/bin/apache-tomcat-9.0.68.tar.gz'
					}
			     }
		}
	}
}
