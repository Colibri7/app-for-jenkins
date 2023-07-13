pipeline {
   
    agent {
        label 'ks2'
    }
    stages {
        stage('1-Build') {
            steps {
                echo 'Start of Stage Build'
                echo 'Building...'
                sh "ifconfig"
                echo 'End if Stage Build'
            }
        }
        stage('2-Test') {
            steps {
                echo 'Start of Stage Test'
                echo 'Testing...'
                sh "ls -la"
                echo 'End if Stage Test'
                
            }
        }
        stage('3-Deploy') {
            steps {
                echo 'Start of Stage Deploy'
                echo 'Deploying...'
                sh """
                echo "Sardro"
                echo "Kenjaev"
                """
                sh "python --version"
                echo 'End if Stage Deploy'
            }
        }
    }
}
