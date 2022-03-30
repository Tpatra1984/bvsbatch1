pipeline {
agent any
environment {
  Subject = "jenkinScripting"
   myvar = 100
}
parameters {
  choice choise : ['UAT' , 'SIT' , 'PROD'] name: 'env'
}
stages {
  stage('Welcome to PAC') {
    steps {
      script {
        /* Direct Variables */
        batchno = 20
        println "my batchno is ${batchno} "
      }
    }
   }
  }
}
