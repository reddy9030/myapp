pipeline{
        agent any
        stages{
            stage('Run Deployment Task'){
            steps{
                echo "Deploy to Test Environment"
            }
            }
            stage('Call Seleium'){
            steps{
                build 'Selenium_Job'
            }
            }
        }
}
