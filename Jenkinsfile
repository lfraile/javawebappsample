pipeline {
    agent { node { label 'dotnet' } } 
    stages {
        stage('Example Build') {
            steps {
                bat 'dotnet --info'
                bat 'terraform version'
            }
        }        
    }
}
