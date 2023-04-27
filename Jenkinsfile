pipeline {
    agent any
    stages {
        stage('Delete this workspace') {
            steps {
                cleanWs()
            }
         }
         stage('Second Stage') {
            steps {
               echo "Second Stage"
            }
         }
         stage('Third Stage') {
            steps {
               echo "Third Stage"
             }
          }
      }
}
