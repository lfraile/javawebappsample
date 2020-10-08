pipeline {
    agent { node { label 'dotnet' } } 
    stages {
        stage('Example Build') {
            steps {
                sh 'dotnet --info'
                //bat 'terraform version'
            }
        }        
    }
}
