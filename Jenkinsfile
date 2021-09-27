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
                if [${Trying}=='Test']
                then
                echo "this is Test"
                
                else
                echo "no condiaitons"
                fi
                """
            }
        }
    }
}