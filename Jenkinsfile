pipeline {
    agent {
        label 'master'
            }
      stages {
        stage('Build') {
            steps { 
                sh'''
                 echo "Git Url: ${GIT_URL}"
                 echo "Git Commiter Name: ${GIT_COMMITTER_NAME}"
                 echo "Git Previous Commit: ${GIT_PREVIOUS_COMMIT}"
                 echo "Git Branch: ${GIT_BRANCH}"
                 echo "Git Author Name: ${GIT_AUTHOR_NAME}"
                 '''
            }
        }
        
    }
    
}
