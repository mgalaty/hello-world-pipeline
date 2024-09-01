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
                    // Set execute permission and run the script
                    sh 'chmod +x hello-world.sh'
                    // Execute the hello-world.sh script
                    sh './hello-world.sh'
                }
            }
        }

        stage('Display README') {
            steps {
                script {
                    // Display the contents of README.md
                    sh 'cat README.md'
                }
            }
        }

    }
}