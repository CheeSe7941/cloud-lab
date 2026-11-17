pipeline {
  agent any
  stages {
    stage("Checkout") {
      steps { git url: "https://github.com/CheeSe7941/cloud-lab.git", branch: "main" }
    }
    stage("Build") {
      steps { sh "docker build -t myflask:test ." }
    }
  }
}
