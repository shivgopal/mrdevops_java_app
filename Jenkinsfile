pipeline{
    agent any
    stages{
         
        stage('Git Checkout'){
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/shivgopal01/devops_java_app.git"
            )
            }
