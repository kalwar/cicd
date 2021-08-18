pipeline {
   agent any

   stages {
      stage("build") {
        steps {
          sh 'npm install'
          sh 'npm build'
        }
      }

      stage("test") {
        steps {
         echo 'testing our app...'
        }
      }

      stage("deploy") {
        steps {
         echo 'deploying our app...'
        }
      }

   }
}
