pipeline {
    agent any
    stages {
        stage('State Hello World as a stage') {
            steps {
                script {
                    sh 'echo "Hello, World!"'
                }
            }
        }

        stage('Run Hello World Script') {
            steps {
                script {
                    // Execute the hello-world.sh script
                    sh './hello-world.sh'
                }
            }
        }


    }
}