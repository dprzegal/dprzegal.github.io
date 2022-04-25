pipeline {
 agent any
  stages {
    stage("build index.html") {
      steps {
        echo "Hello World from Jenkins!!!"
        sh 'mkdir .public'
        sh 'cp -r * .public'
        sh mv .public public'
      }
    }
  }
}
