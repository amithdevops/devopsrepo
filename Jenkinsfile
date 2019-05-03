pipeline {
    agent any
         stages {
            stage('Hello') {
               steps {
                  echo 'Hrello Jenkins'
               }
            }
            stage('Timestamp') {
              steps {
               script {
                 def now = new Date()
                 println now.format("yy/MM/dd.HH.mm", TimeZone.getTimeZone('UTC'))
    }
  } 
}
             stage("Evaluate Master") {
               when {
                // skip this stage unless on Master branch
                branch "master"
               }
              steps {
                 echo "This is master Branch"
                }
             }
             stage("Evaluate dev") {
               when {
                // skip this stage unless on Master branch
                branch "dev"
               }
              steps {
                 echo "This is dev Branch"
                }
             }
             
             stage("Evaluate f1") {
               when {
                // skip this stage unless on Master branch
                branch "f1"
               }
              steps {
                 echo "This is f1 Branch"
                }
             }
             
             
             
             
         }
}
