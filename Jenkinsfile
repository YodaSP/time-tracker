@Library("shared-library") _
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('SharedLib') {
            steps {
                helloWorld()
            }            
            
        }
    }

