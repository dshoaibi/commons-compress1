pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('measurement') {
            steps {
                measure VMs: 30, iterations: 10, warmup: 10, repetitions: 100000
            }
        }
    }
}
