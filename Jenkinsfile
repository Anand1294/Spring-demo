pipeline {
    agent any
    stages {
        stage ('Git clone') {
            steps {
                git url: "https://github.com/Anand1294/Spring-demo.git", branch: "main"
            }
        }
        stage ('Shell Script') {
            steps {
                script {
                    bat "type README.md"
                }
            }
        }
    }
}
