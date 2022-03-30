pipeline {
agent any
environment {
  Subject = "jenkinScripting"
   myvar = 100
}
stages {
  stage('Welcome to PAC') {
    steps {
      script {
        /* Direct Variables */
        batchno = 20
        println "my batchno is ${batchno} "
        println "Thanks for testing the pipeline with GIT"
      }
    }
   }
  }
}
