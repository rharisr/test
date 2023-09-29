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
        stage ('Build Dev'){
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
