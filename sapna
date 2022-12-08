pipeline {
    agent {
		node {
			label "built-in"
		}
	}

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
		stage('Bye') {
            steps {
                echo 'Bye TC'
				
            }
        }
    }
}
