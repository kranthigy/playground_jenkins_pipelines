pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps { 
               step { 
                    echo 'Hello Stage 1, Step 1'
                }
                step { 
                    echo 'Hello Stage 1, Step 2'
                }
            }
        }
        stage('Stage 2') {
            steps { 
                echo 'Hello Stage 2'
            }
        }
    }
}
