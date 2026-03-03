pipeline {
  agent any
  stages{
    
  stage('Clone'){
    steps{
      https://github.com/Krishnananda7/jenkins-simple-demo1.git',
        branch: 'main'
    }
  }
  stage('Run Script'){
    steps{
      sh 'chmod +x script.sh'
      sh './script.sh'
    }
  }
}
}
