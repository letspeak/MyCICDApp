pipeline {
    agent any 
    stages {
        stage('Build'){
            steps {
                sh 'echo "Hello Jenkins"'
            }
        }
        stage('BuildAgain'){
            steps{
                sh '''
                    echo "MultiLine shell steps"
                    ls -lah
                    '''
            }
        }
    }
}