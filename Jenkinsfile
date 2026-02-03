pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo "Code checked out successfully"
            }
        }

        stage('Run Hello World') {
            steps {
                sh './hello.sh'
            }
        }
    }
}

