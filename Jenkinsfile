pipeline {
    agent any

    stages {
        stage('Building Docker Image') {
            steps {
                script{
                  echo 'Hello World'
                  sh 'pwd'
                  sh 'docker build -t myfirstpythonapp .'

                }
 
            }
        }
    }
}
