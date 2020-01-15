pipeline{
    agent {
        docker {
            login --username="22982977893"
            image "ruby"
        }
    }
    stages{
        stage("Build"){
            steps{
                sh "bundle install"
            }
        }
        stage("Tests"){
            steps{
                sh "echo 'simulando um teste automatizado'"
            }
        }
    }
}