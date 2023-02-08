pipeline {
    agent any

    stages {
        
        stage('Building Stage') {
            steps {
                echo 'The Code will be now be built into an artifact'
            }
        }
        stage('Artifact Archiving Stage') {
            steps {
                echo 'The Artifact will be uploaded to an artifact repository'
            }
        }
        stage('Testing Stage') {
            steps {
                echo 'The Artifact will be tested'
            }
        }
        stage('Staging Stage') {
            steps {
                echo 'The Artifact is staged onto the staging server'
            }
        }
        
        stage('Deploy Stage') {
            steps {
                echo 'The software will now be deployed!'
            }
        }
    }    
}
