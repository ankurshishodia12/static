pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello I am Ankur Shishodia"'
        sh '"
                  echo "Multiline shell steps works too"
                  ls -lah
               "'
      }
    }
  }
}
