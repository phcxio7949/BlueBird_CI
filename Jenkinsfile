node {
     stage('Clone repository') {
         checkout scm 
     }

     stage('Build image') {
         app = docker.build("teichae/jenkins:$BUILD_NUMBER") 
     }
}
