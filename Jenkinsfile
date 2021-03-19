pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'ALOHA!'
        measure(VMs: 1, executeParallel: true, executeRCA: true, iterations: 1, repetitions: 1, timeout: 1, versionDiff: 1, warmup: 1)
      }
    }

  }
}