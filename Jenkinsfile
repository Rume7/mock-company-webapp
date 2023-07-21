pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any

   stages {
        stage('Build') {
            steps {
                ./gradlew build
            }
        }
        stage('Test') {
            steps {
                ./gradlew test
            }
        }
   }
}
