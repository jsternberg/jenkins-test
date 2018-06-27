pipeline {
  agent any
  stages {
    def builds = ["Build 1", "Build 2"]
    builds.each {
      stage(it) {
        steps {
          echo "Hello, World!"
        }
      }
    }
  }
}
