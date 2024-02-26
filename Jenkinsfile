pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git 'https://github.com/jglick/simple-maven-project-with-tests.git'

                sh "python3 main.py"
		sh "java Demo.java"

                
            }
        }
    }
}

