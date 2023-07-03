pipeline {
    agent { label 'dev-agent' } 
    stages {
        stage('Checkout SCM') {
            steps {
                echo "Checking out SCM"
                git branch: 'develop',
                credentialsId: 'github-ssh',
                url: 'git@github.com:ikechuqu/moviesStore.git'
            }
        }
    }
}
