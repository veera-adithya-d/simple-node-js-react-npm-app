pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash'
                sh '\. "$HOME/.nvm/nvm.sh"'
                sh 'nvm install 22'
                sh 'npm install' 
            }
        }
    }
}
