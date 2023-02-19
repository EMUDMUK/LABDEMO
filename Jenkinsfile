pipeline {
     agent any
     stages {
          stage("chmod") {
               steps {
                    sh "git update-index --chmod=+x ./gradlew"
               }
          }
          stage("Unit test") {
               steps {
                    sh "./gradlew compileJava"
               }
          }
     }
}
