pipeline {
  agent any
  stages {
      stage("Compilation") {
        steps {
            sh "./mvnw clean install -DskipTest"
        }
      }

      stage("Test") {
        steps {
            sh "./mvnw test -Punit"
        }
      }
   }
}
