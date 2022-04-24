pipeline {
 agent any
  stages {
    stage("build index.html") {
      steps {
        sh"""
              echo "Hello World from Jenkins!!!" > index.html
              git add --all'
              git commit -m "commit"
              git push -u origin main
          """
      }
    }
  }
}
