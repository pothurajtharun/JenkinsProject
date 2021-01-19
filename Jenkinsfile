pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "Building an application..."
            }
        }
        stage("test") {
            steps {
                javac Hello.java
                java Hello
            }
        }
        stage("deploy") {
            steps {
                echo "Deploying an application..."
            }
        }
    }   
}
