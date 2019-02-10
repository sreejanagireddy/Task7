pipeline {
    agent any
    triggers {
        upstream 'Task1, DevProject1, '
    }
    stages {
      stage('FIRST-JOB'){
        steps{
    git 'https://github.com/sreejanagireddy/Task7.git'
        }
  }
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
