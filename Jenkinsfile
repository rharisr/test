pipeline {
    agent any
    stages{
        stage ('Build Master '){
            when {
                branch 'main'
            }
            steps{
                echo "Build Master "
            }
        }
        stage ('Build test'){
            when {
                branch 'test'
            }
            steps {
                 echo 'Build dev '
                 echo 'Build dev '
            }
        }
    }
}
