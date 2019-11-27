pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                 echo "we are in the build block"
            }
        }
        stage('Test') {
            steps {
               echo "we will run some tests"
               grep -Fq "Congratulations" index.html
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy ....."
            }
        }
    }
}
