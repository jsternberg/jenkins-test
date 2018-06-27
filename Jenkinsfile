@Library("imperative-when")

node {
  def builds = ["Build 1": true, "Build 2": false]
  builds.each {
    stage(it.key) {
      when(it.value) {
        echo "Hello, World!"
      }
    }
  }
}
