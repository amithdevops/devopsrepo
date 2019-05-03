pipeline {
    agent any
         stages {
            stage('Hello') {
               steps {
                  echo 'Hrello Jenkins'
               }
            }
            stage('Foo') {
              steps {
               script {
                 def now = new Date()
                 println now.format("yy/MM/dd.HH.mm", TimeZone.getTimeZone('UTC'))
    }
  } 
}
         }
}
