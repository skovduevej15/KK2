pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Starting dummy build step...'
        sleep 2
        echo 'Build completed successfully (dummy).'
      }
    }

    stage('Test') {
      steps {
        echo 'Running dummy tests...'
        sleep 2
        echo 'All dummy tests passed ✅'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Simulating deployment...'
        sleep 2
        echo 'Deployment complete (dummy).'
      }
    }
  }

  post {
    success {
      echo '🎉 Pipeline finished successfully.'
    }
    failure {
      echo '❌ Pipeline failed.'
    }
  }
}
