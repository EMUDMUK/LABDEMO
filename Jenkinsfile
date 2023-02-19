pipeline {
     agent any
     stages {
          stage("Compile") {
               steps {
                    git update-index --chmod=+x ./gradlew 
                    sh "./gradlew compileJava"
               }
          }
     }
}
