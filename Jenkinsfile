pipeline {
    agent any 
    stages {
        stage('Echo File'){
            steps{
            sh"""
            echo "${Trying}"
            """
            }
        }
        stage('Test_condition') {
            steps {
                sh """
                if [${Trying}=='Test'] then
                echo "this is Test"
                elif[${Trying}=='Test1'] then
                echo "this is Test1"
                elif[${Trying}=='Test2'] then
                echo "this is Test2"
                else
                echo "no conditions"
                fi
                """
            }
        }
    }
}