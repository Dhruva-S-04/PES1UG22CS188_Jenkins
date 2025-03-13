pipeline {
    agent any
    
    environment {
        SRN = 'PES1UG22CS188'
        REPO_URL = 'https://github.com/Dhruva-S-04/PES1UG22CS188_Jenkins'
    }
    
    stages {
        
    }
    
    post {
        failure {
            echo 'Pipeline failed'
        }
        success {
            echo 'Pipeline completed successfully'
        }
    }
}
