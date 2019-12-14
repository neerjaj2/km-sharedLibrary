@Library('gitCheckout') _


 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/neerjaj2/km-sharedLibrary.git"
            )
            }
    }
    }
}
