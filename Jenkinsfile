pipeline {
    agent any 
    stages {

        stage('Test_condition') {
            steps {
                sh """
                echo ${Trying}
                if [${Trying}=="Test"]
                then
                echo "this is Test"
                elif[${Trying}=="Test1"]
                then
                echo "this is Test1"
                elif[${Trying}=="Test2"] 
                then
                echo "this is Test2"
                else
                echo "no condiaitons"
                fi
                """
            }
        }
    }
}