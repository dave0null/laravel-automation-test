pipeline {
    agent any 
    parameters {
	string(name: 'STATEMENT', defaultValue: 'hello worldy', description: 'What should I say?')
    }
    stages {
        stage('Example') {
	    steps {
		sh('echo ${STATEMENT}')
		sh('npm i')
		sh('node ./index.js')
	    }
	}
    }
}
