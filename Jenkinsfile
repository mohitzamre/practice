pipeline{
    agent any{
        stages{
            stage('checkout code from scm'){
                steps{
                    sh 'git clone https://github.com/mohitzamre/practice.git'
                }
            }
            stage('done'){
                steps{
                    sh 'echo "job done"'
                }
            }
        }
    }
}
