pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Building application"
      }
    }
    stage('test'){
      steps{
        echo "Running Tests.."
      }
    }
    stage('Run application'){
      steps{
        echo "Run application.."
        #bat 'python app.py'
      }
    }
  }
}
