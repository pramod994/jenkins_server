pipeline {
    agent any 
    stages {
        stage('Stage 1'){
            sh"""
            echo"${Trying}"
            """
        }
        stage('Stage 2') {
            steps {
                sh """
                if [${Trying}=='Test'] then
                    echo "this is Test"
                elif[${Trying}=='Test1'] then
                    echo "this is Test1"
                elif[${Trying}=='Test2'] then
                    echo "this is Test2"
                if
                """
            }
        }
    }
}