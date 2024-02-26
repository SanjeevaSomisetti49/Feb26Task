pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git 'https://github.com/SanjeevaSomisetti49/Feb26Task.git'

                sh "python3 main.py"
		sh "java Demo.java"

                
            }
        }
    }
}

