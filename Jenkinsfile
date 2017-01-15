node {
    stage('Build') {
	checkout scm
        sh "echo Build webapp..."
        sh "mvn compile"
        /* .. todo .. */
    }
    stage('Test') {
        sh "echo Test webapp..."
        sh "mvn test"
    }
    stage('Deploy') {
        /* .. todo .. */
    }
}
