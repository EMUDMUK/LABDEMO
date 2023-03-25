pipeline {
    agent { label 'kubernetes' }
     stages {
          stage("Unit test") {
               steps {
                    sh "./gradlew test"
               }
          }
     }
}
