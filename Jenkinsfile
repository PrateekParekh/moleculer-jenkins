pipeline {
  agent any
  stages {
    stage('local') {
      steps {
        git(branch: 'master', url: 'https://github.com/PrateekParekh/moleculer-jenkins', changelog: true, poll: true)
      }
    }
  }
}