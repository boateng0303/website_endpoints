pipeline{
    agent any

    stages{
        stage('clone'){
            steps{
                sh 'echo this the clone'
            }
        }

        stage('Build'){
            steps{
                sh 'echo kb.com > websites.txt'
            }
        }

        stage('deploy'){
            steps{
                sh 'final deployment done'
            }
        }
    }
}