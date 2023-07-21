pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any

   stages {
        stage('Build') {
            steps {
                ./gradlew assemble
            }
        }
        stage('Test') {
            steps {
                echo 'Running the tests'
                ./gradlew test
            }
        }
   }
}
