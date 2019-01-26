node {
   stage('Preparation') { // for display purposes
      echo 'Preparando...'
      deleteDir()
      checkout scm
      // powershell label: 'Preparando', script: 'echo "Ronaldo"'
   }
   stage('Build') {
      powershell 'echo "Building"'
   }
   stage('Results') {
      powershell 'echo "Results"'
   }
}