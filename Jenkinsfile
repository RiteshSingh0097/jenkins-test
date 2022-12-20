pipeline{
    agent any

    options{
        disableConcurrentBuilds()
    }

    stages{
        stage('Checkout'){
            steps{
                initialize()
                gitCheckout()
            }
        }
    }
}