pipeline{
    agent any{
        stages{
            stage('scm'){
                steps{
                    git branch 'main', url: 'https://innersource.soprasteria.com/rahul.bhure/try_jenkins.git'
                }
            }
            stage('Build){
                steps{
                    echo 'build complete'
                }
            }
            stage('release'){
                steps{
                    echo 'Release done'
                }
            }
        }
    }
}
