pipeline {
     agent kubernetes
     stages {
          stage("Unit test") {
               steps {
                    sh "./gradlew test"
               }
          }
     }
}
