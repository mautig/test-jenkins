node {
    stage("Compilation") {
        sh "./mvnw clean install -DskipTest"
    }

    stage("Test") {
        sh "./mvnw test -Punit"
    }
}
