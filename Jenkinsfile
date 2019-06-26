node {
		stage('Source') {
			git 'git@github.dxc.com:pupendra/HelloWorld.git'
		}
		
		stage('Compile') {
			sh "javac src/HelloWorld.java"
		}
		
		stage('Run') {
			sh "java HelloWorld"
		}
}
