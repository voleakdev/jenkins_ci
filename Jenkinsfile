node {
   def mvnHome
   stage('Initialization') { // for display purposes 
      mvnHome = tool 'M3'
   }
   stage('Build') {
        stage 'Build'
        sh 'mvn clean package'
   }
   stage('Deploy') {
      //----block deploy----
   }
}