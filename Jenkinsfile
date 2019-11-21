pipeline {
agent any
stages {
    stage('Build') {
        steps {
          sh '/usr/local/maven/bin/mvn clean install'
        }
    }
    stage('Test') {
        steps {
          sh '/usr/local/maven/bin/mvn test'
        }
    }
}

}
