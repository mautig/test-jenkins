node {
    stage("Clone project") {
        git branch: 'main', url: ''
    }

    stage("Compilation") {
        sh "./mvnw clean install -DskipTest"
    }

    stage("Test") {
        sh "./mvnw test -Punit"
    }
}