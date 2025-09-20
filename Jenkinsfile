pipeline {
    agent any
    stages {
        stage("Clone Repository") {
            steps {
                git 'https://github.com/Vusena/java-todo.git'
            }
        }

       stage("Build the project") {
    steps {
        sh './gradlew build'
    }
}
stage("Tests") {
    steps {
        sh './gradlew test'
    }
}

    }
}
