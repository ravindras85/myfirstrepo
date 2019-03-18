pipeline {
    agent any

    stages {
        stage ('Build Stage') {

            steps {
                echo "Hello World" {
                    sh 'python hello.py'
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                echo "Hello World Twice" {
                    sh 'python test.py'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo "Hello World Thrice" {
                  }
            }
        }
    }
}
