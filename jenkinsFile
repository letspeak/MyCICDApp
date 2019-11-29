pipeline {
    agent any 
    stages {
        stage('Build'){
            steps {
                sh 'echo "Hello Jenkins"'
            }
        }
        stage('BuildMore'){
            steps{
                sh '''
                    echo "MultiLine shell steps"
                    ls -lah
                    '''
            }
        }
    }
}