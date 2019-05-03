pipeline {
    agent any
         stages {
            stage('Hello') {
               steps {
                  echo 'Hrello Jenkins'
                  echo "TimeStamp: ${Util.getTimeSpanString(System.currentTimeMillis())}"
               }
            }    
        }
}
