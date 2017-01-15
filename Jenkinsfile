node {

    currentBuild.result = "SUCCESS"

    try {
      stage 'Checkout'
	checkout scm
      
      stage 'Build'
        sh "echo Build webapp..."
        sh "mvn compile"

      stage 'Test'
        sh "echo Test webapp..."
        sh "mvn test"
    }
    catch (err) {

        currentBuild.result = "FAILURE"

        throw err
    }
}
