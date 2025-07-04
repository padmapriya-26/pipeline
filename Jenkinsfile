pipeline {
    agent any
    stages {
        stage('build'){
            steps {
                echo "hello world"
            }
        }
        stage('other build'){
            agent {
                label 'headche-label'
            }
            steps{
                echo "other build with master slave"
                sh hostname -i
            }

        }   
        
    }
}
