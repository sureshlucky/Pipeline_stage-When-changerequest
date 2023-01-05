pipeline{
    agent any
    stages{
        stage("BUILD") {
            when {
                changeRequest ( )
            }
            steps{
                echo "Hello World Changing Request"
            }
        }
    }
}
