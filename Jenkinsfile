pipeline {
     agent any
     stages {
         stage('Build') {
             steps {
                 echo 'Building...'
             }
             post {
                 always {
                     jiraSendBuildInfo site: 'nsurendran1991.atlassian.net'
                 }
             }
         }
     }
 }
