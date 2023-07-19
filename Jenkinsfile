pipeline {
  agent any
  stages {
      stage("Compilation") {
        steps {
            sh "./demo/mvnw clean install -DskipTest"
        }
      }

      stage("Test") {
        steps {
            sh "./demo/mvnw test -Punit"
        }
      }
   }
<<<<<<< HEAD
}
=======
}
>>>>>>> origin/main
