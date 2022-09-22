pipeline {
    agent any 
    parameters {
	string(name: 'STATEMENT', defaultValue: 'hello worldy', description: 'What should I say?')
    }
    stages {
        stage('Example') {
	    steps {
		sh('composer --version')
		sh('php --version')
		sh('php artisan --version')
	    }
	}
    }
}
