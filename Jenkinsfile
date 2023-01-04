pipeline{
    agent any
    stages{
        stage("BUILD") {
            when {
                changeRequest ('.*sometext')
            }
            steps{
                echo "Hello World Changing Request"
            }
        }
    }
}
