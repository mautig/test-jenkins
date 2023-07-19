node {
    stage("Compilation") {
        sh "./demo/mvnw clean install -DskipTest"
    }

    stage("Test") {
        sh "./demo/mvnw test -Punit"
    }
}
