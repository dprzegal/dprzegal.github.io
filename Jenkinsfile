pipeline {
 agent any
  stages {
    stage("build index.html") {
      steps {
        sh 'echo '"Hello World from Jenkins!!!" > index.html''
        sh 'git add --all'
        sh 'git commit -m "commit"'
        sh 'git push -u origin main'
      }
    }
  }
}
