pipeline {
    stages {
        stage('Stage Long') {
            steps {
                sh 'echo "This is a very long step description. The intent of this step description is to be so long that it would cause the text to wrap. So we will just keep adding more and more text until that happens."'
            }
        }
        stage('Stage Short') {
            steps {
                sh 'echo "Hello World"'
            }
        }
    }
}