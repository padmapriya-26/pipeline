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
                echo "other bulid with master slave"
                sh hostname -i
            }

        }   
        
    }
}
