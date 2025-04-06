pipeline {
    agent any

    stages {
        stage('Listing Files in multibranch Pipeline') {
            steps {
                git branch: 'main', url: 'https://github.com/AhmedHamdi2/Jenkins-Test.git'
                sh 'ls'
            }
        }
    }
}
