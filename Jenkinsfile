node {
   
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/EugenWiens/JenkinsTestProject.git'
   }
   stage('Build') {
      sh 'echo "Build Pipeline" >> output.txt'
   }
   stage('Results') {
       archiveArtifacts 'output.txt'
   }
}
