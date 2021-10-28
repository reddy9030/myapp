pipeline{
    agent any
    stages{
    stage('SCM Checkout'){
    steps{
        git url: 'https://github.com/reddy9030/devops' , branch: params.BranchName , credentialsId: 'Jenkins_Test'
    }
    }
    }
}
