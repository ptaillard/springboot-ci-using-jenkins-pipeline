node {
    git url: 'https://github.com/ptaillard/springboot-ci-using-jenkins-pipeline.git'
    stage('Build') {
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
