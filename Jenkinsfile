pipeline {
    agent any
    stages{
        stage ('Build Master '){
            when {
                branch 'main
            }
            steps{
                echo "Build Master "
            }
        }
        stage ('Build Dev'){
            when {
                branch 'dev'
            }
            steps {
                 echo 'Build dev '
            }
        }
    }
}
