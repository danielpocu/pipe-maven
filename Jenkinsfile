pipeline {
   agent any
   tools {
      maven 'maven'
      jdk 'jdk1.8.0_151'
   }
   stages {
      stage('Build') {
         steps {
            echo 'Building..'
         echo "PATH = ${PATH}"
         echo "M2_HOME = ${M2_HOME}"
         }
      }
      stage('Test') {
         steps {
            echo 'Building..'
         }
      }
      stage('Deploy') {
         steps {
            echo 'Building..'
         }
      }
   }
}
