pipeline {
   agent any
    stages {
      stage('SCM Checkout') {
         steps {
            git 'https://github.com/Gkasiraju/simple-java-maven-app.git'
        }
    }
    stage ('Build') {
        steps {
            sh '/opt/maven/bin/mvn clean install -Dmaven.test.skip=true'
           this is manikanta:
        }
    }
}
}
