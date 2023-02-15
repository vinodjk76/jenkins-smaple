node { 
                stage('Build') { 
                    echo "Build Stage"
                }
                stage('Test') {
                    
                    echo "Test Stage"
                }
                if (currentBuild.currentResult == 'SUCCESS') {
                    stage('Deploy') {
                    echo "Deploy State" 
                    }
                }
            }
