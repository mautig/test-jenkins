pipeline {
  agent any
  stages {
      stage("Compilation") {
        sh "./mvnw clean install -DskipTest"
      }

      stage("Test") {
        sh "./mvnw test -Punit"
      }
   }
}
