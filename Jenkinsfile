pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                sh """
                if [${Trying}=='Test']
                then 
                echo "this is Test"
                elif[${Trying}=='Test1']
                then
                echo "this is Test1"
                elif[${Trying}=='Test2']
                echo "this is Test2"
                else
                echo "no test"
                if
                """
            }
        }
    }
}