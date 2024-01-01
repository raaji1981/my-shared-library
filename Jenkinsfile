@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        stage('Example Stage') {
            steps {
                // Use the shared step from the library
                mySharedStep()

                // Use a function from the Helper class
                script {
                    Helper.printMessage("Using Helper class")
                }
            }
        }
    }
}
